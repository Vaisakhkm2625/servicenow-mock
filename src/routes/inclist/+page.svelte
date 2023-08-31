<script>
	// Example mock data for incidents

	import incidents from './data.json';
</script>

<header>
	<h1>Incident List</h1>
</header>
<main>
	<table id="incident-table">
		<thead>
			<tr>
				<th>Incident Number</th>
				<th>Description</th>
				<th>Status</th>
			</tr>
		</thead>
		<tbody>
			{#each incidents as incident}
				<tr>
					<td>{incident.number}</td>
					<td>{incident.description}</td>
					<td>{incident.status}</td>
				</tr>
			{/each}
			<!-- Incident data will be added here dynamically -->
		</tbody>
	</table>
</main>

<style>
	/* styles.css */
	body {
		font-family: Arial, sans-serif;
		margin: 0;
		padding: 0;
	}

	header {
		background-color: #333;
		color: #fff;
		text-align: center;
		padding: 1rem;
	}

	main {
		padding: 1rem;
	}

	table {
		width: 100%;
		border-collapse: collapse;
	}

	th,
	td {
		border: 1px solid #ddd;
		padding: 0.5rem;
		text-align: left;
	}
</style>
