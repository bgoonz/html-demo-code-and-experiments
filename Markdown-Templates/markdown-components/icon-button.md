# Icon button

When you need a button that will also contain an icon such as the sign-in buttons, this is the component to use. As can be seen in the code example, the icon SVG is embedded into the `button` element. This is to ensure that we can style the icon appropriately for the various interaction states.

## Left aligned icon example

Sign in with Github

### Code

    <button class="button icon-button">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 500 500"
        aria-hidden="true"
        role="presentation"
      >
        <path
          class="cls-1"
          d="M250 6.39C112.07 6.39.23 118.21.23 256.17c0 110.35 71.56 204 170.81 237 12.48 2.31 17.06-5.42 17.06-12 0-6-.23-25.63-.34-46.5-69.48 15.11-84.15-29.47-84.15-29.47-11.36-28.87-27.73-36.55-27.73-36.55-22.66-15.5 1.71-15.18 1.71-15.18 25.08 1.76 38.29 25.74 38.29 25.74 22.27 38.18 58.43 27.14 72.68 20.76 2.24-16.14 8.72-27.16 15.86-33.4-55.48-6.31-113.8-27.73-113.8-123.44 0-27.27 9.76-49.55 25.74-67-2.6-6.3-11.15-31.7 2.42-66.11 0 0 21-6.7 68.7 25.61a236.78 236.78 0 01125.09 0c47.68-32.36 68.62-25.63 68.62-25.63 13.6 34.41 5.05 59.81 2.45 66.11 16 17.49 25.71 39.77 25.71 67 0 95.94-58.43 117.06-114 123.24 9 7.75 16.94 22.95 16.94 46.26 0 33.42-.29 60.31-.29 68.54 0 6.65 4.5 14.44 17.15 12 99.2-33.07 170.67-126.66 170.67-237C499.77 118.21 387.94 6.39 250 6.39z"
        />
        <path
          class="cls-2"
          d="M94.83 365c-.55 1.25-2.51 1.62-4.28.77s-2.83-2.51-2.24-3.76 2.49-1.63 4.3-.78 2.84 2.53 2.22 3.77zm-3.08-2.28M105 376.3c-1.19 1.1-3.53.59-5.1-1.16s-1.94-4.07-.74-5.19 3.49-.58 5.13 1.16 2 4.07.71 5.19zm-2.39-2.56M114.79 390.68c-1.53 1.07-4 .07-5.58-2.15s-1.53-4.89 0-5.95 4-.11 5.58 2.09 1.53 4.93 0 6zm0 0M128.29 404.58c-1.37 1.51-4.29 1.1-6.42-1s-2.79-4.87-1.42-6.38 4.32-1.08 6.47 1 2.82 4.89 1.37 6.38zm0 0M146.9 412.65c-.61 2-3.41 2.84-6.24 2s-4.68-3.14-4.11-5.12 3.41-2.89 6.26-2 4.67 3.13 4.09 5.12zm0 0M167.34 414.15c.07 2.06-2.33 3.76-5.3 3.8s-5.4-1.6-5.44-3.63 2.35-3.76 5.34-3.82 5.4 1.6 5.4 3.65zm0 0M186.36 410.91c.36 2-1.71 4.07-4.66 4.62s-5.58-.71-5.95-2.7 1.74-4.12 4.64-4.66 5.6.7 6 2.74zm0 0"
        />
      </svg>
      Sign in with Github
    </button>

If you need the icon to be aligned on the right-hand side of the button add the SVG after the button’s text content and use the `right` class.

## Right aligned icon example

Sign up now

### Code

    <button class="button icon-button right">
      Sign up now
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 26 32"
        aria-hidden="true"
        role="presentation"
      >
        <path
          d="M26.3 17.1c0 .6-.2 1.2-.7 1.6L14 30.4c-.4.4-1 .7-1.6.7s-1.2-.2-1.6-.7l-1.3-1.3c-.4-.4-.7-1-.7-1.6s.2-1.2.7-1.6l5.2-5.2H2.1C.8 20.7 0 19.6 0 18.4V16c0-1.2.8-2.3 2.1-2.3h12.6L9.4 8.5c-.9-.9-.9-2.3 0-3.2L10.7 4c.4-.4 1-.7 1.6-.7s1.2.2 1.6.7l11.6 11.6c.6.3.8.9.8 1.5z"
        />
      </svg>
    </button>
