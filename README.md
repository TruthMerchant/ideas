# ideas
A Wordpress plugin for rating ideas (not pictures or portfolios) but written posts and pages 

 Admin interface offers language selection and selects post types to be rated.
   
   for each rated post type:
   
      Whether visitors can rate ideas or only signed in members (for visitors IP = Identity)
      Ratings can be changed at any time and users can list all ideas they have rated
      Whether a rating box is inserted automatically for this post type or is done manually
        with a shortcode on a post by post basis
      When automatic is used rating box insertion can be suppressed on a post by post basis
      Selectable number of stars per rating (typical 5 stars)
      Select whether ratings can be seen by external search engines 
      Select position of ratebox in relatiion to title (single post/psge) or float left or
        right of 'content'/'excerpt' on archives (loops).
      
Front Facing (user) interface automatically inserts a rating box in auro mode

      Each post is intercepted and a rate box inserted using filters:
      the_content and/or the_excerpt, and the_title (suppress in archive loops).
  
  Child themes not needed because the plugin provides overrides using actions:
  
    template_include (override theme template where necessary) and wp_head (override themne css)

  Modular construction without Oject Oriented OO modules.
  
  
  
