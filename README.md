# APIDiccionarioI
https://falfaro21.github.io/APIDiccionarioI/

Implementation of a SPA that shows the user a search engine composed of a text box and a submit button, and when clicking on it uses the search terms entered by the user to request a remote public API (in this case, a dictionary ) a collection of data related to those search terms.

It is also requested to add a "Clear" button, which deletes all data and search terms, thus resetting the previous search.

After receiving the data, the application displays them in the form of a list, so that when the user clicks on one of the listed objects, a detail of the selected object will be displayed, making another request to the remote API, and displaying the new ones on the screen. data.

(Being a SPA, there is no page reload at any time or case)