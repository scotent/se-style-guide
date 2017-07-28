{% include head.html %}

  <body class="component-library">
        
    {% include nav.html %}
    
    <div class="container">

      {% include code-page-breadcrumbs.html %}
      
      <h1 class="component-library">{{ page.title }}</h1>
      
      <div class="row">

        <div class="col-sm-12">

          <div class="demo-box"> 
          <span class="example">Example</span>   
            <!-- ### Put your element demo here ### -->
                    
            {{ content }} 
              
            <!-- ### End element demo ### -->    
          </div>
          
          
          
{% highlight ruby %}
{{ content }}
{% endhighlight %}


          
          
              
          <div class="usage-notes">
            <h2>Usage notes</h2>
          
            <!-- ### Start your usage notes here ###-->
          
               {{page.usage}}
          
            <!-- ### End usage notes ###-->
          </div>


          
        </div>
      </div>

    </div>    

    {% include footer.html %}
 
  </body>

</html>
