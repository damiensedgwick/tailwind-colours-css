# Tailwind Colours 
A collection of colours from the Tailwind CSS framework for use with plain old CSS.

I am forever googling `tailwind colours` and visiting the Tailwind CSS website to
find the colours I need. I thought it would be useful to have a list of all the
colours in one place that could be easily copy/pasta'd into my projects.

## Usage
Simply copy the colour(s) you need into your CSS file and use it as you would any
other CSS variable. I have declared each colour block in such a way that you can
simply copy the entire block and paste it into your CSS file for the colours that 
you need.

For example, I like using css modules. So having a `:root` block in my CSS file
where I can then use the colours as variables is very useful. 

## Example
The following would allow me to easily create various global components using 
the below colours as my base and by adding my own variables to the `:root`
block I can then use the Tailwind colours to build out my own global styles.
```css
:root {
    /* Slate */
    --tw-slate-50: #f8fafc;
    --tw-slate-100: #f1f5f9;
    --tw-slate-200: #e2e8f0;
    --tw-slate-300: #cbd5e1;
    --tw-slate-400: #94a3b8;
    --tw-slate-500: #64748b;
    --tw-slate-600: #475569;
    --tw-slate-700: #334155;
    --tw-slate-800: #1e293b;
    --tw-slate-900: #0f172a;

    /* Teal */
    --tw-teal-50: #f0fdfa;
    --tw-teal-100: #ccfbf1;
    --tw-teal-200: #99f6e4;
    --tw-teal-300: #5eead4;
    --tw-teal-400: #2dd4bf;
    --tw-teal-500: #14b8a6;
    --tw-teal-600: #0d9488;
    --tw-teal-700: #0f766e;
    --tw-teal-800: #115e59;
    --tw-teal-900: #134e4a;

    /* Fuchsia */
    --tw-fuchsia-50: #fdf4ff;
    --tw-fuchsia-100: #fae8ff;
    --tw-fuchsia-200: #f5d0fe;
    --tw-fuchsia-300: #f0abfc;
    --tw-fuchsia-400: #e879f9;
    --tw-fuchsia-500: #d946ef;
    --tw-fuchsia-600: #c026d3;
    --tw-fuchsia-700: #a21caf;
    --tw-fuchsia-800: #86198f;
    --tw-fuchsia-900: #701a75;
    
    /* My Custom Variables */
    --primary-color: var(--tw-teal-500);
    --secondary-color: var(--tw-slate-500);
    
    --primary-background: var(--tw-slate-50);
    --secondary-background: var(--tw-slate-100);
    
    /* etc... */
}
```

## Contributing
If you find any errors or would like to add any colours, please feel free to. I
imagine the colour palette will change over time as Tailwind CSS evolves.