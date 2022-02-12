# All lessons about css/scss
---------------------------
>> 2.3 - 2.4 - 2.6 - 2.7:
* clip-path: polygon()
* animation: name duration timing-function delay iteration-count direction fill-mode
* backface-visibility: hidden -> fix shaking back part of rotate and other ...
* animation-fill-mode: backwards -> initial state of 0% keyframes
* box-shadow: x y b rgba

>> 3.4 - 3.8 - 3.10:
* * -> (0, 0 , 0, 0)
* inherit box-sizing
* responsive font-size for user browser
* atomic design
* itcss - s-max

>> 4.4 - 4.6 - 4.7:
* mixin -> unrelatived selectors
* extend -> relatived selectors
* cls -> clear
* echo nul > file -> touch file
* ren name1 name2
* use \ in cmd -> / in terminal
* w flag -> keep watching -w
* g flag -> install globally >< --save

>> 5.5 - 5.6 - 5.8 - 5.9 - 5.10 - 5.11 - 5.12 - 5.13 - 5.14 - 5.15 - 5.16 - 5.17 - 5.18 - 5.19 - 5.20 - 5.21 - 5.22 - 5.23 - 5.24:
* :not
* native css calc -> in visual formatting model -> mix units
* ^= - *= - $= -> attribute selector

* --webkit-background-clip: text -> background fits text
* color: transparent -> opacity color of text
* skew
* text-shadow
* trick not hover animation -> smart selector
* outline - outline-offset
* > -> app direct first child

* perspective -> 3d
* -webkit-box-decoration-break: clone -> trick break text content with 2 box same styling
* background-blend-mode: screen -> blend mode ps
* prefixer

* clip-path make overflow not active

* shape-outside with float -> align outside content with shape
* transform cannot declare 2 time with different value
* SMALL BUG: 
    padding image with short paragraph
    real image in devtools in right bottom for view image

* filter - blur - brightness

* object-fit: cover -> maintain aspect ratio and cover parent element
* video - source element
* SMALL BUG:
    2 line when hover and not hover in 2 sides image -> overflow: hidden [x]

* solid linear gradient

* input not inherit font and color properties
* sibling selector: + ~
* ::-webkit-input-placeholder
* :placeholder-shown
* :focus
* :invalid
* position: absolute make child known as relative
* trick compose button with anchor link use &

* trick use display: inline-block for wrap width

* radial-gradient

* :checked -> trick input checkbox or radio hidden
* cubic bezier
* trick background-size with background-position

* transform-origin -> change origin of element when transform

* display: table - table-cell
* column count - gap (default 1em) - rule
* hyphens -> break word with hyphen -> magazine and newspaper

* :target -> href

>> 6.3 - 6.4 - 6.7 - 6.8 - 6.9 - 6.10 - 6.11 - 6.12:
* @content and @if directive
* media queries use default font-size of browser - use em not rem (1em = 16px)
* media queries follow by order code

* display: table-row

* srcset attribute -> density descriptor 1x
* picture tag - source attribute -> art direction
* media attribute -> media queries

* width descriptor 300w
* sizes attribute -> media queries

* min-resolution == -webkit-min-device-pixel-ratio

* backdrop-filter
* @supports feature queries

* npm command
* fix postcss
* cannot use -b 'last 10 versions'

* ::selection -> change style select text
* hover: none in media queries
----------------------------------
# New features
* popup mouseover background to close
* navigation click link close nav and scroll to internal part