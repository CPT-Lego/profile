HTML

always starts with

<!DOCTYPE html?>      # all HTML docs start with this
<html>      # opening tag


  <head>
         # Link to CSS (which is in same directory in this case)

    <!-- Page's intelligence goes here = meta tags --> e.g. for SEO
    # NB: NOT BUILDING BODY OF PAGE
    # NB: WE ARE JUST SETTING CONTENT/KEYWORDS THE HELP TO DISPLAY / INDEX YOUR PAGE


E.G.

    <title>Page Title. Maximum length 60-70 characters</title> # THIS WILL BE TITLE OF TAB IN BROWSER, SEARCH RESULTS ETC (for example)
    <meta name="description" content="Page description. No longer than 155 characters.">  # SAME APPLIES AS FOR <TITLE> ABOVE

    <meta charset="utf-8">        # ALWAYS USE THIS

    CAN THEN ALSO ADD
    FOR FB <meta property="og:title"> - AND THE REST OF THE FB TAGS, ALL START WITH OG:
    FOR TWITTER <meta name="twitter:card" > AND THE REST OF TWITTER TAGS, ALL START WITH twitter=



  </head>

  <body>

    <!-- Page's content = displayed on the page -->


  <h1>[...]</h1>
  <h2>[...]</h2>
  <h3>[...]</h3>
  <h4>[...]</h4>
  <h5>[...]</h5>
  <h6>[...]</h6>


Paragraphs

  <p>
  Text goes here

    You can emphasize <em>some words</em>, and even <strong>more if needed</strong>
  </p>


  Lists
  <ul> # UNORDERED LIST
  <li>Milk</li>
  <li>Butter</li>
  </ul>

  <ol> # ORDERED LIST
  <li>Argentina</li>
  <li>France</li>
  </ol>

  Images

  <img src="link" alt="Le Wagon logo">   # Source, and alt = text for if picture doesn't load, or for visually impaired

  Forms

  <form>
  <input type="email">
  <input type="password">
  <input type="submit" value="Log in">
  </form>



  </body>
</html>  # closing tag
