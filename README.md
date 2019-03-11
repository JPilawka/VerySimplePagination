# VerySimplePagination
Very simple to use pagination vue script. Based on Bootstrap.

## Installation
Current version require to be downloaded into components folder.
Importing into app:

    import Pagination from './components/Pagination.vue'
    
into export default object add: 
    
    components: {
    Pagination
  }

## Usage:

     <pagination
         :items="VariableWithContentToBePaginated"
         @page:update="updatePage"
         :currentPage="currentPageVariable"
         :pageSize="NumberOfItemsOnPage">
      </pagination>
      
      
      methods: {
         updatePage(pageNumber) {
            this.currentPage = pageNumber;
          }
      
      }

  
