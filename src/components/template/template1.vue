        <template>
          <div class="hello">
      <head_head></head_head>



  <h1>CSS Custom Properties are awesome</h1>

  <h1 class="intro">Here is some generic content</h1>

<blockquote>This is a blockquote, where I could have a testimonial talking about how great my services are</blockquote>

<p>Lorem ipsum <a href="#" data-tool-tip="a cool tool tip">dolor sit amet</a>, consectetur adipiscing elit. Nulla a efficitur nisi, id vulputate nulla. Donec dictum nulla et ipsum imperdiet suscipit. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Praesent bibendum sodales est, nec eleifend urna finibus nec. </p>


<div class="decorations">
  <h1>We can decorate sections!</h1>
  <h2 class="section-with-deco">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section-with-deco">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section-with-deco">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section-with-deco">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section-with-deco">Add add content after links</h2>
  <p>Pellentesque <a href="example.pdf">habitant</a> morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. <a href="https://#" target="_blank">Mauris placerat</a> eleifend leo.</p>
</div>


<div class="counters">
  <h1>We can number sections!</h1>
  <h2 class="section">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <h2 class="section">Section title here</h2>
  <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
  <ol>
    <li>I'm a list item</li>
    <li>me too!</li>
    <li>me three</li>
    <li>Hello there</li>
  </ol>
  <ol>
    <li>I'm a list item</li>
    <li>me too!</li>
    <li>me three</li>
    <li>Hello there</li>
  </ol>
</div>



  <!-- <img src="../../assets/icons/sent.png" alt="" srcset=""> -->
 





   
      </div>
      
        
        </template>

      <script>

      import head_head from '../header/header.vue'

      export default {
      
        
        data:function(){
          return{
           
          }
        },

          components:{
              head_head,
          },

          methods:{
        
    

          
          }
        
      }
      </script>

      <style lang="scss" scoped>
        // @import url('https://fonts.googleapis.com/css?family=Unica+One|Vollkorn')
         @import url('https://fonts.googleapis.com/css?family=Unica+One|Vollkorn');

         $ff-ss: 'Unica One';
         $ff-s: 'Vollkorn';
         
         $clr-red: #c31;
         $clr-black: rgba(black, 1);
         $clr-gray: rgba(black, .7);

         body {
           font-size: 1rem;
           text-align: center;
           font-family: $ff-s;
           line-height: 1.4;
           color: $clr-gray;
         }

        h1, h2, h3, h4, h5 {
          font-family: $ff-ss;
          text-transform: uppercase;
          line-height: .9;
          color: #c31;
        }

        h2 {
          margin-top: 1.2em;
          margin-bottom: 0;
        }
        
        p {
          margin-top: .25em;
        }
        
        a {
          color: $clr-red;
        }
        
        .intro {
          font-size: 5rem;
        }
        

        blockquote {
          font-size: 2rem;
          color: $clr-black;
        }
        
        blockquote::before {
          content: open-quote;
        }
        
        blockquote::after {
          content: close-quote;
        }
        
        a[data-tool-tip] {
          position: relative;
        }
        
        a[data-tool-tip]::after {
          content: attr(data-tool-tip);
          display: block;
          position: absolute;
          background-color: $clr-gray;
          padding: 1em 3em;
          color: white;
          border-radius: 5px;
          font-size: .8em;
          bottom: 0;
          left: 0;
          white-space: nowrap;
          transform: scale(0);
          transition:
            transform ease-out 150ms,
            bottom ease-out 150ms;
        }
        
        a[data-tool-tip]:hover::after {
          transform: scale(1);
          bottom: 100%;
        }
        
        .decorations {
          padding: 7em;
        }

        .section-with-deco::before {
          font-family: 'Font Awesome 5 Free';
          font-weight: 900;
          content: '\f0e7';
          display: block;
          margin-bottom: 5px;
        }
        
        a[href$=".pdf"]::after {
          font-family: 'Font Awesome 5 Free';
          content: ' \f1c1'
        }
        
        a[href^="http"]::after {
          font-family: 'Font Awesome 5 Free';
          content: ' \f35d';
          font-weight: 900;
          font-size: .8em;
        }
        
        .counters {
          background: lightgray;
          text-align: left;
          padding: 5em 8em;
          margin-top: 7em;
          
          counter-reset: counter-name;
        }
        
        .section { position: relative; }
        
        .section::before {
          counter-increment: counter-name;
          content: counter(counter-name);
          position: absolute;
          left: -2.5em;
          top: -.5em;
          background: white;
          width: 2em;
          height: 2em;
          border-radius: 50%;
          display: flex;
          justify-content: center;
          align-items: center;
          border: 3px solid $clr-gray;
          color: $clr-gray;
          box-sizing: border-box;
        }
        
        .counters ol {
          list-style: none;
        }
        
        .counters li::before {
          counter-increment: ordered-list;
          content: 'list item ' counter(ordered-list) ') ';
          font-size: .8em;
          color: $clr-red;
        }

   

      </style>
      
        
       