<template lang="pug">
    section
        b-container
            h1
                | Pricing
            b-row
                b-col
                    b-card(header="featured" header-tag="header" no-body)
                        b-card-body
                            b-card-title
                                | Card Title
                            b-card-sub-title.mb-2
                                | Card Sub Title
                            b-card-text
                                | Some quick example text to build on the card title and make up the bulk of the card's content.
                        b-list-group(flush)
                            b-list-group-item
                                | Cras justo odio
                            b-list-group-item
                                | Dapibus ac facilisis in
                            b-list-group-item
                                | Vestibulum at eros
                        b-card-body
                            b-button(href="#" variant="primary")
                                | Go somewhere
                b-col
                    b-card(header="featured" header-tag="header" footer="Card Footer" footer-tag="footer" title="Title")
                        b-card-text
                            | Header and footers using props.
                        b-button(href="#" variant="primary")
                            | Go somewhere
                b-col
                    b-card(header="featured" header-tag="header" footer="Card Footer" footer-tag="footer" title="Title")
                        b-card-text
                            | Header and footers using props.
                        b-button(href="#" variant="primary")
                            | Go somewhere
</template>
