# Attribute Widget Category Relation Resource

## Tulajdonságok

<ResourceProperties :resource="'attribute_widget_category_relation'" :lang="'hu'"/>

## Endpoints

[//]: <> (GET ENDPOINT)
<ResourceEndpoint :resource="'attribute_widget_category_relation'" :endpoint="'get'" :lang="'hu'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (GETCOLLECTION ENDPOINT)
<ResourceEndpoint :resource="'attribute_widget_category_relation'" :endpoint="'getCollection'" :lang="'hu'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/json/get_page.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/xml/get_page.xml

</template>

</ResourceEndpoint>

[//]: <> (POST ENDPOINT)
<ResourceEndpoint :resource="'attribute_widget_category_relation'" :endpoint="'post'" :lang="'hu'">

<template v-slot:request>

<<< @/docs/fixtures/api/attribute_widget_category_relation/request/post.json

</template>

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (PUT ENDPOINT)
<ResourceEndpoint :resource="'attribute_widget_category_relation'" :endpoint="'put'" :lang="'hu'">

<template v-slot:request>

<<< @/docs/fixtures/api/attribute_widget_category_relation/request/put.json

</template>

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/attribute_widget_category_relation/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (DELETE ENDPOINT)
<ResourceEndpoint :resource="'attribute_widget_category_relation'" :endpoint="'delete'" :lang="'hu'"/>

