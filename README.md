# how the web works

part one

- HTTP stands for Hypertext Transfer Protocol and is a set of rules that allow you to transfer files like images, videos, text, etc. through the web
- a URL (uniform resource locator) is the address of a web page
- DNS stands for Domain Name System and this turns domains into IP addresses (a unique string of characters that idenfity each computer)
- A query string is aa set of characters tacked onto the end of a URL
  https://www.tech.com/search?query=database+tools&star_rating=4&order=alphabetical
  everything after ? is part of the string (?key1=value1&key2=value2...)
- GET and POST: GET has no side effects since it's just allowing you to retrieve information but POST does because it sends data to the server
- an HTTP request is when you make a request on a server to a host
- an HTTP response is the server's response to your request
- an HTTP header allows you to pass more information between you and the server
- HTTP headers/repsonse request -
  Example 1: Content-Type: text/html
  Example 2: Content-Type: application/json
  Example 3: Content-Type: image/png
- brower makes a request to the IP address for that URL (including the headers); your server sends a response with a status code (200 if ✔️),

  PART TWO: pratice tools

- MacBook-Pro-4:~ shahidulislam$ curl -H "Accept: application/json" "https://icanhazdadjoke.com/search?term=pirate"
  {"current_page":1,"limit":20,"next_page":1,"previous_page":1,"results":[{"id":"QuscibaMClb","joke":"What does a pirate pay for his corn? A buccaneer!"},{"id":"2gii3LeN7Ed","joke":"Why couldn't the kid see the pirate movie? Because it was rated arrr!"},{"id":"SvzIBAQS0Dd","joke":"What did the pirate say on his 80th birthday? Aye Matey!"},{"id":"exXSCtkOKe","joke":"Why do pirates not know the alphabet? They always get stuck at \"C\"."},{"id":"SnOf2gqjiqc","joke":"Why are pirates called pirates? Because they arrr!"}],"search_term":"pirate","status":200,"total_jokes":5,"total_pages":1}
  - 104.21.66.15
  - done

Part Three: explore dev tools
done
Part Four:
