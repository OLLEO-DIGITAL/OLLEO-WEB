<script context="module">
	export function load({ error, status }) {
		return {
			props: {
				status,
				error
			}
		};
	}
  </script>
  
  <script>
	export let status;
	export let error;
  </script>
  
 <div>
	 <h1>{status}</h1>
	 <p>{error.message}</p>
 </div> 

  <style lang="scss">
	  div {
		  display: flex;
		  justify-content: center;
		  align-content: center;
		  
		  h1 {
			  font-size: 5rem;
		  }
	  }
  </style>