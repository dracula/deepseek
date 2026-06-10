/* ==UserStyle==
@name         DeepSeek Dracula Theme
@namespace    github.com/Miggycraft
@version      1.0.0
@description  Dracula color scheme for DeepSeek dark mode code blocks and UI
@author       Miggy
@match        https://chat.deepseek.com/*
==/UserStyle== */

@-moz-document domain("chat.deepseek.com") {

/* =====================================================
   DRACULA PALETTE
   ===================================================== */
:root {
    --dracula-dark-background: #20212B;
    --dracula-background:      #282a36;
    --dracula-comment:         #6272A4;
    --dracula-selection:       #44475A;
    --dracula-cyan:            #8BE9FD;
    --dracula-orange:          #FFB86C;
    --dracula-yellow:          #F1FA8C;
    --dracula-pink:            #FF79C6;
    --dracula-purple:          #BD93F9;
    --dracula-green:           #50FA7B;
    --dracula-foreground:      #F8F8F2;
    --dracula-red:             #FF5555;
}

/* =====================================================
   DARK THEME — SURFACE & BACKGROUND TOKENS
   ===================================================== */
body[data-ds-dark-theme] {
    /* Page backgrounds */
    --dsw-static-neutral-bluish-950: #20212B;   /* base bg */
    --dsw-static-neutral-bluish-900: #282a36;   /* sidebar fill */
    --dsw-static-neutral-bluish-875: #282a36;   /* layer-1 */
    --dsw-static-neutral-bluish-850: #2e3040;   /* layer-2, code block bg */
    --dsw-static-neutral-bluish-800: #44475A;   /* layer-3, cards, overlays */
    --dsw-static-neutral-bluish-750: #44475A;   /* tooltips, selector */

    /* Borders & muted tones */
    --dsw-static-neutral-bluish-700: #6272A4;
    --dsw-static-neutral-bluish-600: #6272A4;   /* captions */
    --dsw-static-neutral-bluish-60:  #282a36;
    --dsw-static-neutral-bluish-500: #7b8fc4;
    --dsw-static-neutral-bluish-400: #9ba9d0;   /* tertiary labels */
    --dsw-static-neutral-bluish-300: #bbc4de;   /* secondary labels */
    --dsw-static-neutral-bluish-200: #ccd2e8;
    --dsw-static-neutral-bluish-150: #d8ddef;
    --dsw-static-neutral-bluish-100: #e8eaf4;
    --dsw-static-neutral-bluish-75:  #eef0f8;
    --dsw-static-neutral-bluish-50:  #F8F8F2;   /* primary text */
    --dsw-static-neutral-bluish-00:  #F8F8F2;

    /* Brand / accent */
    --dsw-static-deepseek-50:  #f0eaff;
    --dsw-static-deepseek-100: #e0d2fe;
    --dsw-static-deepseek-200: #c8aafd;
    --dsw-static-deepseek-300: #b088fc;
    --dsw-static-deepseek-400: #8BE9FD;   /* link / brand-text → cyan */
    --dsw-static-deepseek-450: #BD93F9;   /* brand-primary → purple */
    --dsw-static-deepseek-500: #a97dfa;   /* hover */
    --dsw-static-deepseek-600: #7a5abf;
    --dsw-static-deepseek-700-delete: #5a3e99;
    --dsw-static-deepseek-800: #44475A;
    --dsw-static-deepseek-900: #383a4a;

    /* Scrollbar */
    --scroll-color:       rgba(98, 114, 164, 0.4);
    --scroll-color-hover: rgba(189, 147, 249, 0.6);
}

/* =====================================================
   DARK CODE BLOCKS — PRISM TOKEN COLORS
   ===================================================== */

/* Base text & background */
.md-code-block.md-code-block-dark code[class*="language-"],
.md-code-block.md-code-block-dark pre[class*="language-"] {
    color: #F8F8F2;
}
.md-code-block.md-code-block-dark :not(pre) > code[class*="language-"],
.md-code-block.md-code-block-dark pre[class*="language-"] {
    background: #282a36;
}

/* Selection */
.md-code-block.md-code-block-dark pre[class*="language-"]::selection,
.md-code-block.md-code-block-dark pre[class*="language-"] ::selection,
.md-code-block.md-code-block-dark code[class*="language-"]::selection,
.md-code-block.md-code-block-dark code[class*="language-"] ::selection,
.md-code-block.md-code-block-dark pre[class*="language-"]::-moz-selection,
.md-code-block.md-code-block-dark pre[class*="language-"] ::-moz-selection,
.md-code-block.md-code-block-dark code[class*="language-"]::-moz-selection,
.md-code-block.md-code-block-dark code[class*="language-"] ::-moz-selection {
    background: #44475A;
}

/* Comments */
.md-code-block.md-code-block-dark .token.comment,
.md-code-block.md-code-block-dark .token.prolog,
.md-code-block.md-code-block-dark .token.doctype,
.md-code-block.md-code-block-dark .token.cdata {
    color: #6272A4;
}

/* Punctuation */
.md-code-block.md-code-block-dark .token.punctuation {
    color: #F8F8F2;
}

/* Tags, delimiters → cyan */
.md-code-block.md-code-block-dark .token.delimiter.important,
.md-code-block.md-code-block-dark .token.selector .parent,
.md-code-block.md-code-block-dark .token.tag,
.md-code-block.md-code-block-dark .token.tag .token.punctuation {
    color: #8BE9FD;
}

/* Numbers, booleans, constants → yellow */
.md-code-block.md-code-block-dark .token.attr-name,
.md-code-block.md-code-block-dark .token.boolean,
.md-code-block.md-code-block-dark .token.boolean.important,
.md-code-block.md-code-block-dark .token.number,
.md-code-block.md-code-block-dark .token.constant,
.md-code-block.md-code-block-dark .token.selector .token.attribute {
    color: #F1FA8C;
}

/* Class names, properties, variables → cyan */
.md-code-block.md-code-block-dark .token.class-name,
.md-code-block.md-code-block-dark .token.key,
.md-code-block.md-code-block-dark .token.parameter,
.md-code-block.md-code-block-dark .token.property,
.md-code-block.md-code-block-dark .token.property-access,
.md-code-block.md-code-block-dark .token.variable {
    color: #8BE9FD;
}

/* Strings → yellow */
.md-code-block.md-code-block-dark .token.attr-value,
.md-code-block.md-code-block-dark .token.inserted,
.md-code-block.md-code-block-dark .token.color,
.md-code-block.md-code-block-dark .token.selector .token.value,
.md-code-block.md-code-block-dark .token.string,
.md-code-block.md-code-block-dark .token.string .token.url-link {
    color: #F1FA8C;
}

/* Builtins, regex → pink */
.md-code-block.md-code-block-dark .token.builtin,
.md-code-block.md-code-block-dark .token.keyword-array,
.md-code-block.md-code-block-dark .token.package,
.md-code-block.md-code-block-dark .token.regex {
    color: #FF79C6;
}

/* Functions → green */
.md-code-block.md-code-block-dark .token.function,
.md-code-block.md-code-block-dark .token.selector .token.class,
.md-code-block.md-code-block-dark .token.selector .token.id {
    color: #50FA7B;
}

/* Keywords, operators, selectors → pink */
.md-code-block.md-code-block-dark .token.atrule .token.rule,
.md-code-block.md-code-block-dark .token.combinator,
.md-code-block.md-code-block-dark .token.keyword,
.md-code-block.md-code-block-dark .token.operator,
.md-code-block.md-code-block-dark .token.pseudo-class,
.md-code-block.md-code-block-dark .token.pseudo-element,
.md-code-block.md-code-block-dark .token.selector,
.md-code-block.md-code-block-dark .token.unit {
    color: #FF79C6;
}

/* Deleted, important → red */
.md-code-block.md-code-block-dark .token.deleted,
.md-code-block.md-code-block-dark .token.important {
    color: #FF5555;
}

/* this keyword → cyan */
.md-code-block.md-code-block-dark .token.keyword-this,
.md-code-block.md-code-block-dark .token.this {
    color: #8BE9FD;
}

/* Whitespace markers → comment */
.md-code-block.md-code-block-dark .token.token.tab:not(:empty)::before,
.md-code-block.md-code-block-dark .token.token.cr::before,
.md-code-block.md-code-block-dark .token.token.lf::before,
.md-code-block.md-code-block-dark .token.token.space::before {
    color: #6272A4;
}

/* Font weight / style */
.md-code-block.md-code-block-dark .token.important,
.md-code-block.md-code-block-dark .token.keyword-this,
.md-code-block.md-code-block-dark .token.this,
.md-code-block.md-code-block-dark .token.bold {
    font-weight: 700;
}
.md-code-block.md-code-block-dark .token.delimiter.important {
    font-weight: inherit;
}
.md-code-block.md-code-block-dark .token.italic {
    font-style: italic;
}

/* =====================================================
   MARKDOWN LANGUAGE-SPECIFIC TOKENS
   ===================================================== */
.md-code-block.md-code-block-dark .language-markdown .token.title,
.md-code-block.md-code-block-dark .language-markdown .token.title .token.punctuation {
    color: #8BE9FD;
    font-weight: 700;
}
.md-code-block.md-code-block-dark .language-markdown .token.blockquote.punctuation {
    color: #FF79C6;
}
.md-code-block.md-code-block-dark .language-markdown .token.code {
    color: #8BE9FD;
}
.md-code-block.md-code-block-dark .language-markdown .token.hr.punctuation {
    color: #8BE9FD;
}
.md-code-block.md-code-block-dark .language-markdown .token.url .token.content {
    color: #50FA7B;
}
.md-code-block.md-code-block-dark .language-markdown .token.url-link {
    color: #F1FA8C;
}
.md-code-block.md-code-block-dark .language-markdown .token.list.punctuation {
    color: #FF79C6;
}
.md-code-block.md-code-block-dark .language-markdown .token.table-header,
.md-code-block.md-code-block-dark .language-json .token.operator {
    color: #F8F8F2;
}
.md-code-block.md-code-block-dark .language-scss .token.variable {
    color: #8BE9FD;
}

/* =====================================================
   LINE NUMBERS & GUTTERS
   ===================================================== */
.md-code-block.md-code-block-dark .line-numbers.line-numbers .line-numbers-rows {
    background: rgba(40, 42, 54, 0.6);
    border-right: 1px solid #20212B;
}
.md-code-block.md-code-block-dark .line-numbers .line-numbers-rows > span::before {
    color: rgba(98, 114, 164, 0.855);
}
.md-code-block.md-code-block-dark pre[id].linkable-line-numbers span.line-numbers-rows > span:hover::before {
    background-color: rgba(98, 114, 164, 0.15);
}

/* =====================================================
   LINE HIGHLIGHT
   ===================================================== */
.md-code-block.md-code-block-dark .line-highlight.line-highlight {
    background: linear-gradient(90deg, rgba(68, 71, 90, 0.5) 70%, rgba(68, 71, 90, 0.4));
}
.md-code-block.md-code-block-dark .line-highlight.line-highlight::before,
.md-code-block.md-code-block-dark .line-highlight.line-highlight[data-end]::after {
    color: #282a36;
    background-color: #6272A4;
    box-shadow: 0 1px #44475A;
}

/* =====================================================
   RAINBOW BRACES
   ===================================================== */
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-1,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-5,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-9  { color: #F1FA8C; }

.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-2,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-6,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-10 { color: #FF79C6; }

.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-3,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-7,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-11 { color: #8BE9FD; }

.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-4,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-8,
.md-code-block.md-code-block-dark .rainbow-braces .token.token.punctuation.brace-level-12 { color: #BD93F9; }

/* =====================================================
   DIFF HIGHLIGHT
   ===================================================== */
.md-code-block.md-code-block-dark pre.diff-highlight > code .token.token.deleted:not(.prefix),
.md-code-block.md-code-block-dark pre > code.diff-highlight .token.token.deleted:not(.prefix) {
    background-color: rgba(255, 85, 85, 0.15);
}
.md-code-block.md-code-block-dark pre.diff-highlight > code .token.token.inserted:not(.prefix),
.md-code-block.md-code-block-dark pre > code.diff-highlight .token.token.inserted:not(.prefix) {
    background-color: rgba(80, 250, 123, 0.12);
}

/* =====================================================
   TOOLBAR (copy button etc.)
   ===================================================== */
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > a,
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > button {
    color: #282a36;
    background: #BD93F9;
}
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > a:hover,
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > a:focus,
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > button:hover,
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > button:focus {
    background: rgba(189, 147, 249, 0.855);
    text-decoration: none;
}
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > span,
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > span:hover,
.md-code-block.md-code-block-dark div.code-toolbar > .toolbar.toolbar > .toolbar-item > span:focus {
    color: #282a36;
    background: #6272A4;
}

/* =====================================================
   COMMAND LINE PROMPT
   ===================================================== */
.md-code-block.md-code-block-dark .command-line .command-line-prompt {
    border-right: 1px solid #44475A;
}
.md-code-block.md-code-block-dark .command-line .command-line-prompt > span::before {
    color: rgba(98, 114, 164, 0.855);
}

._546d736 ._254829d{
    background: linear-gradient(
    90deg,
    color-mix(in srgb, var(--dracula-background) 0%, transparent) 0%,
    color-mix(in srgb, var(--dracula-background) 50%, transparent) 20.23%,
    var(--dracula-background) 40.62%
    ) !important;}

}