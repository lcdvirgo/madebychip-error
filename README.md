madebychip-error
================


Custom error pages for my portfolio website madebychip.com if website is down. 
heroku config:set \
  ERROR_PAGE_URL=madebychip-error.herokuapp.com \
  MAINTENANCE_PAGE_URL=madebychip-error.herokuapp.com
Heroku guide: https://devcenter.heroku.com/articles/error-pages#customize-pages
