# persist_search_filter
It saves the search input text and active facets to sessionStorage whenever the user types or selects a filter Generates a unique storage key based on the current page URL (so each view has its own saved state) When a search view is rendered in the DOM, it automatically restores the previously saved search by replaying the input events and Enterkey
<br>
Author : Saad Khattak
