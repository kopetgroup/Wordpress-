## CheatSheet

theming made simple

List kategori: 
```
<?php
  /*
    Get Category Lists
  */
  $categories = get_the_category();
  if(!empty($categories)){
    echo '<a class="navbar-item" href="'.esc_url( get_category_link($categories[0]->term_id)).'">'.esc_html($categories[0]->name).'</a>';
  }
?>
```
