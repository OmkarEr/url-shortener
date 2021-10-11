# url-shortener

A url-shortener app using :
 * Spring Boot 2.5.5 (Spring Web[MVC] + Spring Data Redis)
 * Guava 31.0.1
 * Common Validator 1.7

URLs
 * POST /rest/url with body as long_url_string - For creating the short url from long url
 * GET /rest/url/{id} - For retrieving the long URL from short id
