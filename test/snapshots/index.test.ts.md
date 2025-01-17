# Snapshot report for `test/index.test.ts`

The actual snapshot is saved in `index.test.ts.snap`.

Generated by [AVA](https://ava.li).

## Should return @font-face declaration as snapshots

> @font-face declaration without the family wrapped in quotes

    '@font-face { font-style: italic;font-weight: 400;font-family: Helvetica;src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\'); } @font-face { font-style: normal;font-weight: 400;font-family: Helvetica;src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\'); } @font-face { font-style: normal;font-weight: 500;font-family: Helvetica;src: local(\'Helvetica Medium\'),local(\'Helvetica-Medium\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\'); } @font-face { font-style: normal;font-weight: bold;font-family: Helvetica;src: local(\'Helvetica Bold\'),local(\'Helvetica-Bold\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\'); }'

> @font-face declaration with the family wrapped in quotes

    '@font-face { font-style: italic;font-weight: 400;font-family: \'Helvetica Neue\';src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\'); } @font-face { font-style: normal;font-weight: 400;font-family: \'Helvetica Neue\';src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\'); } @font-face { font-style: normal;font-weight: 500;font-family: \'Helvetica Neue\';src: local(\'Helvetica Medium\'),local(\'Helvetica-Medium\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\'); } @font-face { font-style: normal;font-weight: bold;font-family: \'Helvetica Neue\';src: local(\'Helvetica Bold\'),local(\'Helvetica-Bold\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\'); }'

> @font-face declaration with additional fontFace styles

    '@font-face { font-style: italic;font-weight: 400;font-family: Helvetica;src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\');font-display: swap;-moz-font-feature-settings: "tnum", "liga"; } @font-face { font-style: normal;font-weight: 400;font-family: Helvetica;src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\');font-display: swap;-moz-font-feature-settings: "tnum", "liga"; } @font-face { font-style: normal;font-weight: 500;font-family: Helvetica;src: local(\'Helvetica Medium\'),local(\'Helvetica-Medium\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\');font-display: swap;-moz-font-feature-settings: "tnum", "liga"; } @font-face { font-style: normal;font-weight: bold;font-family: Helvetica;src: local(\'Helvetica Bold\'),local(\'Helvetica-Bold\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\');font-display: swap;-moz-font-feature-settings: "tnum", "liga"; }'

## Should return font styles as snapshots

> Font styles as objects with fallback families

    {
      s14: {
        i400: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '14px',
          fontStyle: 'italic',
          fontWeight: 400,
          letterSpacing: 'initial',
          lineHeight: '18px',
        },
        n400: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '14px',
          fontStyle: 'normal',
          fontWeight: 400,
          letterSpacing: 'initial',
          lineHeight: '18px',
        },
      },
      s20: {
        n500: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20px',
          fontStyle: 'normal',
          fontWeight: 500,
          letterSpacing: '0.29px',
          lineHeight: '22px',
        },
        n500_caps: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20px',
          fontStyle: 'normal',
          fontWeight: 500,
          letterSpacing: '1px',
          lineHeight: '1px',
          textTransform: 'uppercase',
        },
        n500_lower: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20px',
          fontStyle: 'normal',
          fontWeight: 500,
          letterSpacing: 'initial',
          lineHeight: 'normal',
          textTransform: 'lowercase',
        },
        nBold: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20rem',
          fontStyle: 'normal',
          fontWeight: 'bold',
          letterSpacing: '0.29em',
          lineHeight: '22em',
        },
      },
      sFooBar: {
        nBold: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: 'FooBar',
          fontStyle: 'normal',
          fontWeight: 'bold',
          letterSpacing: '0.29em',
          lineHeight: '22em',
        },
      },
    }

> Font styles as objects without fallback families

    '@font-face { font-style: italic;font-weight: 400;font-family: Helvetica;src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\'); } @font-face { font-style: normal;font-weight: 400;font-family: Helvetica;src: local(\'Helvetica Regular\'),local(\'Helvetica-Regular\'); } @font-face { font-style: normal;font-weight: 500;font-family: Helvetica;src: local(\'Helvetica Medium\'),local(\'Helvetica-Medium\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\'); } @font-face { font-style: normal;font-weight: bold;font-family: Helvetica;src: local(\'Helvetica Bold\'),local(\'Helvetica-Bold\'), url(./font-file.eot) format(\'embedded-opentype\'), url(./font-file.woff) format(\'woff\'), url(./font-file.woff2) format(\'woff2\'), url(./font-file.ttf) format(\'ttf\'); }'

> Font styles with additional font styles

    {
      s14: {
        i400: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '14px',
          fontStyle: 'italic',
          fontWeight: 400,
          letterSpacing: 'initial',
          lineHeight: '18px',
          textRendering: 'optimizeLegibility',
        },
        n400: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '14px',
          fontStyle: 'normal',
          fontWeight: 400,
          letterSpacing: 'initial',
          lineHeight: '18px',
          textRendering: 'optimizeLegibility',
        },
      },
      s20: {
        n500: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20px',
          fontStyle: 'normal',
          fontWeight: 500,
          letterSpacing: '0.29px',
          lineHeight: '22px',
          textRendering: 'optimizeLegibility',
        },
        n500_caps: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20px',
          fontStyle: 'normal',
          fontWeight: 500,
          letterSpacing: '1px',
          lineHeight: '1px',
          textRendering: 'optimizeLegibility',
          textTransform: 'uppercase',
        },
        n500_lower: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20px',
          fontStyle: 'normal',
          fontWeight: 500,
          letterSpacing: 'initial',
          lineHeight: 'normal',
          textRendering: 'optimizeLegibility',
          textTransform: 'lowercase',
        },
        nBold: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: '20rem',
          fontStyle: 'normal',
          fontWeight: 'bold',
          letterSpacing: '0.29em',
          lineHeight: '22em',
          textRendering: 'optimizeLegibility',
        },
      },
      sFooBar: {
        nBold: {
          fontFamily: 'Helvetica, -apple-system, BlinkMacSystemFont',
          fontSize: 'FooBar',
          fontStyle: 'normal',
          fontWeight: 'bold',
          letterSpacing: '0.29em',
          lineHeight: '22em',
          textRendering: 'optimizeLegibility',
        },
      },
    }
