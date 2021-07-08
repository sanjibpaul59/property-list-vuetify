<template>
  <v-card light class="rounded-0 ma-3">
    <v-row justify="center">
      <v-expansion-panels accordion multiple>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header1 = !header1"
            class="font-weight-medium"
            >Budget
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header1 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content>
            <v-row class="d-flex justify-space-around ml-1">
              <v-col>
                <pill-button value="1.5 Lacs" />
              </v-col>
              <v-col>
                <pill-button value="3.5 Cr" />
              </v-col>
            </v-row>
            <v-row>
              <v-col>
                <v-range-slider
                  max="50"
                  min="-50"
                  track-color="grey lighten-1"
                  color="amber darken-2"
                ></v-range-slider>
              </v-col>
            </v-row>
          </v-expansion-panel-content>
        </v-expansion-panel>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header2 = !header2"
            class="font-weight-medium"
            >Budget
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header2 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content>
            <v-row class="d-flex justify-around mt-2">
              <pill-button />
              <pill-button />
              <pill-button :outline="outline" color="amber darken-2" />
              <pill-button :outline="outline" color="amber darken-2" />
              <pill-button :outline="outline" color="amber darken-2" />
            </v-row>
          </v-expansion-panel-content>
        </v-expansion-panel>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header3 = !header3"
            class="font-weight-medium"
            >Property Status
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header3 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content>
            <v-radio-group column multiple>
              <v-radio color="amber darken-2" value="newProject">
                <template v-slot:label>
                  <div>
                    New Project
                    <strong class="amber--text text--darken-2">253</strong>
                  </div>
                </template>
              </v-radio>
              <v-radio color="amber darken-2" value="newProject">
                <template v-slot:label>
                  <div>
                    Resale Properties
                    <strong class="amber--text text--darken-2">453</strong>
                  </div>
                </template>
              </v-radio>
            </v-radio-group>
          </v-expansion-panel-content>
        </v-expansion-panel>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header4 = !header4"
            class="font-weight-medium"
            >Possession
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header4 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content>
            <v-radio-group column multiple>
              <v-radio color="amber darken-2" value="readyToMove">
                <template v-slot:label>
                  <div>
                    Ready to move
                  </div>
                </template>
              </v-radio>
              <v-radio color="amber darken-2" value="sixMonths">
                <template v-slot:label>
                  <div>
                    In 6 Months
                  </div>
                </template>
              </v-radio>
              <v-radio color="amber darken-2" value="oneYear">
                <template v-slot:label>
                  <div>
                    In 1 Year
                  </div>
                </template>
              </v-radio>
            </v-radio-group>
          </v-expansion-panel-content>
        </v-expansion-panel>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header5 = !header5"
            class="font-weight-medium"
            >Age of Property
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header5 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content></v-expansion-panel-content>
        </v-expansion-panel>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header6 = !header6"
            class="font-weight-medium"
            >Listed By
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header6 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content></v-expansion-panel-content>
        </v-expansion-panel>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header7 = !header7"
            class="font-weight-medium"
            >Property Type
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header7 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content></v-expansion-panel-content>
        </v-expansion-panel>
        <v-expansion-panel>
          <v-expansion-panel-header
            @click="header8 = !header8"
            class="font-weight-medium"
            >Amenities
            <template v-slot:actions>
              <v-icon small color="grey">
                {{ header8 === true ? "mdi-minus" : "mdi-plus" }}
              </v-icon>
            </template>
          </v-expansion-panel-header>
          <v-expansion-panel-content></v-expansion-panel-content>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-row>
  </v-card>
</template>

<script>
import PillButton from "./PillButton.vue"
export default {
  components: { PillButton },
  data: () => ({
    outline: false,
    headers: [
      "Budget",
      "Budget",
      "Property Status",
      "Possession",
      "Age of Property",
      "Listed By",
      "Property Type",
      "Amenities",
    ],
    header1: false,
    header2: false,
    header3: false,
    header4: false,
    header5: false,
    header6: false,
    header7: false,
    header8: false,
  }),
}
</script>

<style lang="scss" scoped></style>
