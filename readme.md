Early prototype of Collector App post module made with Vue.js and Firebase

Models

collection: {
	id: number,
	name: string,
	type: string,
	items: number,
	physical: true,
	foto: string
}

colItem {
	id: number,
	collectionid: number,
	itemNumber: string,
	title: string,
	picture: string,
	gotit: true,
	damage: string,
	geo: string,
	price: number,
	comment: string,
}