<script>
$(document).ready(function(){

    $('table.display').DataTable( {
        paging: true,
        stateSave: true,
        searching: true
    }
        );
});
</script>

<table id="sampleTable" class="display">
   <thead>
      <tr>
         <th>Parameter</th>
         <th>Description</th>
         <th>Type</th>
         <th>Default Value</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>Parameter 1</td>
         <td>Sample description
         </td>
         <td>Sample type</td>
         <td>Sample default value</td>
      </tr>
      <tr>
         <td>Parameter 2</td>
         <td>Sample description
         </td>
         <td>Sample type</td>
         <td>Sample default value</td>
      </tr>
    <tr>
       <td>Parameter 3</td>
       <td>Sample description
       </td>
       <td>Sample type</td>
       <td>Sample default value</td>
    </tr>
      <tr>
         <td>Parameter 4</td>
         <td>Sample description
         </td>
         <td>Sample type</td>
         <td>Sample default value</td>
      </tr>
   </tbody>
</table>
