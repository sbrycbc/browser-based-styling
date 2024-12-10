# browser-based-styling

## Webkit-based browsers

### 

- -webkit-appearance
- -webkit-mask
- -webkit-box-shadow
- -webkit-border-radius
- -webkit-text-stroke
- -webkit-transform
- -webkit-backface-visibility

### 

- -webkit-animation
- -webkit-transition
- -webkit-transform

### 

- -webkit-background-clip
- -webkit-background-origin
- -webkit-mask-image
- -webkit-mask-size
- -webkit-mask-repeat

### 

- -webkit-flex
- -webkit-align-items
- -webkit-justify-content

### 

- -webkit-line-clamp
- -webkit-font-smoothing
- -webkit-user-select

### 

- -webkit-filter
- -webkit-backdrop-filter


## Firefox

###

- -moz-appearance
- -moz-border-radius
- -moz-box-shadow

###

- -moz-user-select
- -moz-focus-ring

###

- -moz-scrollbar-width
- -moz-scrollbar-color
- -moz-box-sizing

###

- -moz-osx-font-smoothing

###

- -moz-element
- -moz-tab-size

## Different Styles for Firefox and Chrome

/* For Firefox */
@-moz-document url-prefix() {
    .specific {
        color: red; /* Firefox-specific style */
    }
}

/* For Chrome and WebKit-based browsers */
@media screen and (-webkit-min-device-pixel-ratio: 0) {
    .specific {
        color: blue; /* Chrome-specific style */
    }
}


