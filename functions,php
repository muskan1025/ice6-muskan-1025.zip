<?php
// Enqueue the parent theme stylesheet
function astra_cms2_enqueue_styles() {
    wp_enqueue_style('astra-parent-style', get_template_directory_uri() . '/style.css');
    wp_enqueue_style('astra-cms2-style', get_stylesheet_uri(), array('astra-parent-style'));
}
add_action('wp_enqueue_scripts', 'astra_cms2_enqueue_styles');

// Add the advertising notice banner
function astra_cms2_banner() {
    echo '<div class="advertising-banner">This is your advertising notice banner!</div>';
}
add_action('astra_header_before', 'astra_cms2_banner');