# freehub-css
responsive styles for freehub (for 2019)

## pages
- [x] [/](https://johngravois.com/freehub-css/index.html) freehub landing page
  - [x] header
  - [x] body
  - [x] footer
- [ ] [/:org/edit](https://johngravois.com/freehub-css/bikebbq/edit/index.html)
- [ ] [/session/new](https://johngravois.com/freehub-css/session/new/index.html)
- [ ] [/forgot/](https://johngravois.com/freehub-css/forgot/index.html)
- [ ] [/users/:id/edit/](https://johngravois.com/freehub-css/users/123/index.html)
- [ ] [/:org/](https://johngravois.com/freehub-css/bikebbq/index.html)
- [ ] [/:org/visits/yyyy/mm/dd](https://johngravois.com/freehub-css/bikebbq/visits/2019/1/1/index.html)
- [ ] [/:org/people/:id](https://johngravois.com/freehub-css/bikebbq/people/123/index.html)
- [ ] [/:org/people/:id/visits/](https://johngravois.com/freehub-css/bikebbq/people/123/visits/index.html)
- [ ] [/:org/people/:id/visits/:id/](https://johngravois.com/freehub-css/bikebbq/people/123/visits/456/edit/index.html)
- [ ] [/:org/people/:id/visits/:id/edit](https://johngravois.com/freehub-css/bikebbq/people/123/visits/456/edit/index.html)
- [ ] [/:org/people/:id/services/new](https://johngravois.com/freehub-css/bikebbq/people/123/services/new/index.html)
- [ ] [/:org/people/new](https://johngravois.com/freehub-css/bikebbq/people/new/index.html) coop person edit view (new or existing)
- [ ] [/:org/reports](https://johngravois.com/freehub-css/bikebbq/reports/index.html)

## tweaks required in the app
1. `.column left` > `.column-left`
1. `.column` > `.column-right`
1. `null` > `.column` (for pages with a single column)
1. some html :cheese: needed to be moved in the header and footer

### misc

- [ ] clean up the rats nest of new css
- [ ] yank movie plugin
- [ ] can we use built in browser calendar stuff?
  - [ ] if not we might be able to get rid of the calendar date picker _and_ jquery
- [ ] do we need ms- prefixed css-grid for IE?
- [x] light gray border around main content
- [x] drop-shadow without a background image
- [ ] make sure site is still easily navigable by keyboard
- [x] "For those who which" https://github.com/asalant/freehub/pull/42
- [ ] put visit arrows on _top_ of the table of visitors (so you dont have to move the mouse)
