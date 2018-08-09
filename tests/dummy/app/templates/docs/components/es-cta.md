# CTA

<div class="docs-es-cta">
    {{#docs-demo as |demo|}}
        {{#demo.example name='es-cta-mobile.hbs'}}
            <div class="mobile-layout">
                {{#es-cta label='Click Here'}}
                    Some message with some extra context and different styles in use. Click to view.
                {{/es-cta}}
            </div>
        {{/demo.example}}
        {{demo.snippet 'es-cta-mobile.hbs'}}
    {{/docs-demo}}

    {{#docs-demo as |demo|}}
        {{#demo.example name='es-cta-wide.hbs'}}
            <div class="wide-layout">
                {{#es-cta label='Click Here'}}
                    Some message with some extra context and different styles in use. Click to view.
                {{/es-cta}}
            </div>
        {{/demo.example}}
    {{demo.snippet 'es-cta-wide.hbs'}}
    {{/docs-demo}}
</div>