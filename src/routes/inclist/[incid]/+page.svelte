<script>
	import { page } from '$app/stores';
	import data from '../data.json';

	$: path = $page.params.incid;
	$: inc = data.filter((item) => item.number === path)[0];
</script>

<div class="container">
	<div class="row">
		<div class="col-sm-6">
			<div class="form-group row">
				<label for="number" class="control-label col-sm-2">number:</label><br />
				<div class="col-sm-8">
					<input type="text" id="number" name="number" class="form-control" value={inc.number} /><br
					/>
				</div>
			</div>

			<div class="form-group row">
				<label for="number" class="control-label col-sm-2">number:</label><br />
				<div class="col-sm-8">
					<input type="text" id="number" name="number" class="form-control" value={inc.number} /><br
					/>
				</div>
			</div>

			<div class="form-group row">
				<label for="caller" class="control-label col-sm-2">caller:</label><br />
				<div class="col-sm-8">
					<input type="text" id="caller" name="caller" class="form-control" value={inc.caller} /><br
					/>
				</div>
			</div>

			<div class="form-group row">
				<label for="requestedFor " class="control-label col-sm-2">requestedFor :</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="requestedFor "
						name="requestedFor "
						class="form-control"
						value={inc.requestedFor}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="service" class="control-label col-sm-2">service:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="service"
						name="service"
						class="form-control"
						value={inc.service}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="configurationitem" class="control-label col-sm-2">configurationitem:</label><br
				/>
				<div class="col-sm-8">
					<input
						type="text"
						id="configurationitem"
						name="configurationitem"
						class="form-control"
						value={inc.configurationitem}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="category" class="control-label col-sm-2">category:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="category"
						name="category"
						class="form-control"
						value={inc.category}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="subcategory" class="control-label col-sm-2">subcategory:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="subcategory"
						name="subcategory"
						class="form-control"
						value={inc.subcategory}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="complianceImpact" class="control-label col-sm-2">complianceImpact:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="complianceImpact"
						name="complianceImpact"
						class="form-control"
						value={inc.complianceImpact}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="impactedDivision" class="control-label col-sm-2">impactedDivision:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="impactedDivision"
						name="impactedDivision"
						class="form-control"
						value={inc.impactedDivision}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="impactedLocation" class="control-label col-sm-2">impactedLocation:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="impactedLocation"
						name="impactedLocation"
						class="form-control"
						value={inc.impactedLocation}
					/><br />
				</div>
			</div>
		</div>

		<div class="col-sm-6">
			<div class="form-group row">
				<label for="contactType" class="control-label col-sm-2">contactType:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="contactType"
						name="contactType"
						class="form-control"
						value={inc.contactType}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="state" class="control-label col-sm-2">state:</label><br />
				<div class="col-sm-8">
					<input type="text" id="state" name="state" class="form-control" value={inc.state} /><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="impactUrgency" class="control-label col-sm-2">impactUrgency:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="impactUrgency"
						name="impactUrgency"
						class="form-control"
						value={inc.impactUrgency}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="priority" class="control-label col-sm-2">priority:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="priority"
						name="priority"
						class="form-control"
						value={inc.priority}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="assignmentGroup" class="control-label col-sm-2">assignmentGroup:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="assignmentGroup"
						name="assignmentGroup"
						class="form-control"
						value={inc.assignmentGroup}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="assignedTo" class="control-label col-sm-2">assignedTo:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="assignedTo"
						name="assignedTo"
						class="form-control"
						value={inc.assignedTo}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="language" class="control-label col-sm-2">language:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="language"
						name="language"
						class="form-control"
						value={inc.language}
					/><br />
				</div>
			</div>

			<div class="form-group row">
				<label for="actualStartTime" class="control-label col-sm-2">actualStartTime:</label><br />
				<div class="col-sm-8">
					<input
						type="text"
						id="actualStartTime"
						name="actualStartTime"
						class="form-control"
						value={inc.actualStartTime}
					/><br />
				</div>
			</div>
		</div>
	</div>

	<div class="row">
		<div class="form-group row">
			<label for="call" class="control-label col-sm-2">short discription:</label><br />
			<div class="col-sm-10">
				<input
					type="text"
					id="call"
					name="call"
					class="form-control"
					value={inc.shortdescription}
				/><br />
			</div>
		</div>
	</div>
</div>
