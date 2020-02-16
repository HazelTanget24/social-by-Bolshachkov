<template>
  <div>
        <v-row class="text-left">
            <v-col cols="10">
                <h1 class="green--text text--darken-2">
                    <v-icon large color="green darken-2">mdi-account-outline</v-icon>
                    Иван Иванов
                </h1>
            </v-col>
        </v-row>
        <v-row class="text-left">
            <v-col cols="2">
                <img src="https://randomuser.me/api/portraits/men/7.jpg" style="max-width: 100%">
            </v-col>
            <v-col cols="10" class="text-left">
                <p>
                    Веб-сайт: <a href="..." target="_blank">...</a>
                </p>
                <p>
                    E-mail: <a href="mailto:...">...</a>
                </p>
                <p>
                    Город: ...
                </p>
                <p>
                    Место работы: ...
                </p>
            </v-col>
        </v-row>
        <!-- Карточка пользователя начало  -->
        <v-card
             class="mx-auto"
            color="#26c6da"
            dark
            max-width="400"
             >
            <v-card-title>
                 <v-icon
                      large
                      left
                    >
                 mdi-twitter
                </v-icon>
                <span class="title font-weight-light">Twitter</span>
             </v-card-title>

        <v-card-text class="headline font-weight-bold">
             "Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well."
        </v-card-text>

        <v-card-actions>
            <v-list-item class="grow">
            <v-list-item-avatar color="grey darken-3">
        <v-img
            class="elevation-6"
            src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
          ></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title>Evan You</v-list-item-title>
        </v-list-item-content>

        <v-row
          align="center"
          justify="end"
        >
          <v-icon class="mr-1">mdi-heart</v-icon>
          <span class="subheading mr-2">256</span>
          <span class="mr-1">·</span>
          <v-icon class="mr-1">mdi-share-variant</v-icon>
          <span class="subheading">45</span>
        </v-row>
      </v-list-item>
    </v-card-actions>
  </v-card>
  <!--Конец карточки -->
    </div>
</template>