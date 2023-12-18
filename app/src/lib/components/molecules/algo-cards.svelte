<script>
	import AlgoCard from '$lib/components/atoms/algo-card.svelte';
	import Regression from '$lib/icons/regression.svelte';
	import NeuralNetwork from '$lib/icons/neural-network.svelte';
	import Svm from '$lib/icons/svm.svelte';
	import RandomForest from '$lib/icons/random-forest.svelte';
	import KNearestNeighbor from '$lib/icons/k-nearest-neighbor.svelte';
	import KMeansClustering from '$lib/icons/k-means-clustering.svelte';
	import DecisionTree from '$lib/icons/decision-tree.svelte';
</script>

<div class="flex flex-row flex-wrap gap-4 justify-center">
	<AlgoCard title="Regression">
		<Regression slot="algo-figure" />
	</AlgoCard>

	<AlgoCard title="Support vector machine">
		<Svm slot="algo-figure" />
	</AlgoCard>

	<AlgoCard title="Random Forest">
		<RandomForest slot="algo-figure" />
	</AlgoCard>

	<AlgoCard title="K-Nearest Neighbor">
		<KNearestNeighbor slot="algo-figure" />
	</AlgoCard>

	<AlgoCard title="K-Means Clustering">
		<KMeansClustering slot="algo-figure" />
	</AlgoCard>

	<AlgoCard title="Decision Tree">
		<DecisionTree slot="algo-figure" />
	</AlgoCard>
</div>
