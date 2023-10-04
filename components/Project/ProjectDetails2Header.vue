<template>
  <section
    class="page-header proj-det bg-img parallaxie valign mt-60"
    style="background-color: #000"
    :style="`background-image: url(${projectHeaderData.projectHeaderImage}); background-position: center top; background-repeat: no-repeat; background-size: contain;`"
    data-overlay-dark="4"
  >
   <!-- <div class="container">
      <div class="row">
        <div class="col-lg-7 col-md-9">
          <div class="cont">
            <h3 style="color: rgba(178,141,73,1); font-weight: bold;">{{ projectHeaderData.title.small }}</h3>
            <h2>{{ projectHeaderData.title.big }}</h2>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-3">
          <div class="item mt-30">
            <h6>Client</h6>
            <p>
              <NuxtLink :to="projectHeaderData.clientURLLink">
                {{ projectHeaderData.clientURLName }}
              </NuxtLink>
            </p>
          </div>
        </div>
        <div class="col-lg-3">
          <div class="item mt-30">
            <h6>Date</h6>
            <p>{{ projectHeaderData.date }}</p>
          </div>
        </div>
        <div class="col-lg-3">
          <div class="item mt-30">
            <h6>Categories</h6>
            <p>
              <NuxtLink
                v-for="(cat, index) in projectHeaderData.categories"
                :to="cat.link"
                :key="cat.id"
              >
                {{ cat.name }}
                {{
                  projectHeaderData.categories.length != index + 1 ? " ," : ""
                }}
              </NuxtLink>
            </p>
          </div>
        </div>
        <div class="col-lg-3">
          <div class="item mt-30">
            <h6>Tags</h6>
            <p>
              <NuxtLink
                v-for="(tag, index) in projectHeaderData.tags"
                to="tag.link"
                :key="tag.id"
              >
                {{ tag.name }}
                {{ projectHeaderData.tags.length != index + 1 ? " ," : "" }}
              </NuxtLink>
            </p>
          </div>
        </div>
      </div>
    </div> -->
  </section>
</template>

<script setup>
const { projectHeaderData } = defineProps(["projectHeaderData"]);
</script>
