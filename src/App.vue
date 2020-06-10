<template>
  <ve-tree :data="chartData" :settings="chartSettings"></ve-tree>
</template>

<script>
const treeData = {
  id: "1",
  name: "Şımarık",
  bilezik: "TR-34-",
  children: [
    {
      id: "3",
      name: "Rezzan",
      bilezik: "TR-34-99-3-2020",
      Cinsiyet: "disi",
      children: [
        {
          id: "12",
          name: "Çılgın",
          bilezik: "TR-34-99-2-2021",
          Cinsiyet: "erkek",
          children: [
            {
              id: "104",
              name: "bambam",
              bilezik: "TR-34-99-94-2021",
              Cinsiyet: "disi"
            },
            {
              id: "139",
              name: "altin",
              bilezik: "TR-34-99-4-2022",
              Cinsiyet: "erkek"
            },
            {
              id: "165",
              name: "derin",
              bilezik: "TR-34-99-30-2022",
              Cinsiyet: "disi"
            },
            {
              id: "167",
              name: "bordo",
              bilezik: "TR-34-99-32-2022",
              Cinsiyet: "erkek"
            },
            {
              id: "183",
              name: "rezzan",
              bilezik: "TR-34-99-48-2022",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "13",
          name: "Rimel",
          bilezik: "TR-34-99-3-2021",
          Cinsiyet: "disi",
          children: [
            {
              id: "90",
              name: "nigar",
              bilezik: "TR-34-99-80-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "106",
              name: "seker",
              bilezik: "TR-34-99-96-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "156",
              name: "zencefil",
              bilezik: "TR-34-99-21-2022",
              Cinsiyet: "disi"
            },
            {
              id: "219",
              name: "masuk",
              bilezik: "TR-34-99-84-2022",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "14",
          name: "bayram",
          bilezik: "TR-34-99-4-2021",
          Cinsiyet: "erkek",
          children: [
            {
              id: "32",
              name: "masuk",
              bilezik: "TR-34-99-22-2021",
              Cinsiyet: "disi"
            },
            {
              id: "49",
              name: "nine",
              bilezik: "TR-34-99-39-2021",
              Cinsiyet: "disi"
            },
            {
              id: "67",
              name: "zipir",
              bilezik: "TR-34-99-57-2021",
              Cinsiyet: "disi"
            },
            {
              id: "78",
              name: "nine",
              bilezik: "TR-34-99-68-2021",
              Cinsiyet: "disi"
            },
            {
              id: "88",
              name: "asli",
              bilezik: "TR-34-99-78-2021",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "15",
          name: "ciklet",
          bilezik: "TR-34-99-5-2021",
          Cinsiyet: "disi",
          children: [
            {
              id: "31",
              name: "cankus",
              bilezik: "TR-34-99-21-2021",
              Cinsiyet: "disi"
            },
            {
              id: "60",
              name: "kontes",
              bilezik: "TR-34-99-50-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "81",
              name: "cips",
              bilezik: "TR-34-99-71-2021",
              Cinsiyet: "disi"
            },
            {
              id: "115",
              name: "findik",
              bilezik: "TR-34-99-105-2021",
              Cinsiyet: "disi"
            },
            {
              id: "123",
              name: "cino",
              bilezik: "TR-34-99-113-2021",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "16",
          name: "mert",
          bilezik: "TR-34-99-6-2021",
          Cinsiyet: "erkek",
          children: [
            {
              id: "79",
              name: "mavname",
              bilezik: "TR-34-99-69-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "124",
              name: "kismet",
              bilezik: "TR-34-99-114-2021",
              Cinsiyet: "disi"
            },
            {
              id: "132",
              name: "bal",
              bilezik: "TR-34-99-122-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "151",
              name: "firfir",
              bilezik: "TR-34-99-16-2022",
              Cinsiyet: "erkek"
            },
            {
              id: "158",
              name: "cazibe",
              bilezik: "TR-34-99-23-2022",
              Cinsiyet: "disi"
            }
          ]
        }
      ]
    },
    {
      id: "4",
      name: "aristo",
      bilezik: "TR-34-99-4-2020",
      Cinsiyet: "erkek",
      children: [
        {
          id: "17",
          name: "cango",
          bilezik: "TR-34-99-7-2021",
          Cinsiyet: "erkek",
          children: [
            {
              id: "71",
              name: "balon",
              bilezik: "TR-34-99-61-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "80",
              name: "gizi",
              bilezik: "TR-34-99-70-2021",
              Cinsiyet: "disi"
            },
            {
              id: "87",
              name: "bidik",
              bilezik: "TR-34-99-77-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "103",
              name: "serseri",
              bilezik: "TR-34-99-93-2021",
              Cinsiyet: "disi"
            },
            {
              id: "113",
              name: "kinali",
              bilezik: "TR-34-99-103-2021",
              Cinsiyet: "erkek"
            }
          ]
        },
        {
          id: "35",
          name: "bal",
          bilezik: "TR-34-99-25-2021",
          Cinsiyet: "erkek",
          children: []
        },
        {
          id: "45",
          name: "kinali",
          bilezik: "TR-34-99-35-2021",
          Cinsiyet: "disi",
          children: []
        },
        {
          id: "47",
          name: "simli",
          bilezik: "TR-34-99-37-2021",
          Cinsiyet: "erkek"
        },
        {
          id: "191",
          name: "paytak",
          bilezik: "TR-34-99-56-2022",
          Cinsiyet: "disi"
        }
      ]
    },
    {
      id: "5",
      name: "bicir",
      bilezik: "TR-34-99-5-2020",
      Cinsiyet: "disi",
      children: [
        {
          id: "21",
          name: "pepe",
          bilezik: "TR-34-99-11-2021",
          Cinsiyet: "disi",
          children: [
            {
              id: "53",
              name: "pepe",
              bilezik: "TR-34-99-43-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "66",
              name: "nine",
              bilezik: "TR-34-99-56-2021",
              Cinsiyet: "disi"
            },
            {
              id: "75",
              name: "nagis",
              bilezik: "TR-34-99-65-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "83",
              name: "mercan",
              bilezik: "TR-34-99-73-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "126",
              name: "bayram",
              bilezik: "TR-34-99-116-2021",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "22",
          name: "bicir",
          bilezik: "TR-34-99-12-2021",
          Cinsiyet: "erkek",
          children: [
            {
              id: "42",
              name: "cankus",
              bilezik: "TR-34-99-32-2021",
              Cinsiyet: "disi"
            },
            {
              id: "72",
              name: "bicirik",
              bilezik: "TR-34-99-62-2021",
              Cinsiyet: "disi"
            },
            {
              id: "84",
              name: "dudu",
              bilezik: "TR-34-99-74-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "97",
              name: "masuk",
              bilezik: "TR-34-99-87-2021",
              Cinsiyet: "disi"
            },
            {
              id: "99",
              name: "bulut",
              bilezik: "TR-34-99-89-2021",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "23",
          name: "malibu",
          bilezik: "TR-34-99-13-2021",
          Cinsiyet: "erkek",
          children: [
            {
              id: "44",
              name: "findik",
              bilezik: "TR-34-99-34-2021",
              Cinsiyet: "disi"
            },
            {
              id: "112",
              name: "cankus",
              bilezik: "TR-34-99-102-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "180",
              name: "gofret",
              bilezik: "TR-34-99-45-2022",
              Cinsiyet: "disi"
            },
            {
              id: "182",
              name: "ares",
              bilezik: "TR-34-99-47-2022",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "24",
          name: "cino",
          bilezik: "TR-34-99-14-2021",
          Cinsiyet: "erkek",
          children: [
            {
              id: "43",
              name: "bibis",
              bilezik: "TR-34-99-33-2021",
              Cinsiyet: "disi"
            },
            {
              id: "56",
              name: "pirtik",
              bilezik: "TR-34-99-46-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "57",
              name: "seker",
              bilezik: "TR-34-99-47-2021",
              Cinsiyet: "disi"
            },
            {
              id: "120",
              name: "ninem",
              bilezik: "TR-34-99-110-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "128",
              name: "rifki",
              bilezik: "TR-34-99-118-2021",
              Cinsiyet: "disi"
            }
          ]
        },
        {
          id: "25",
          name: "cango",
          bilezik: "TR-34-99-15-2021",
          Cinsiyet: "disi",
          children: [
            {
              id: "39",
              name: "seker",
              bilezik: "TR-34-99-29-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "51",
              name: "apollo",
              bilezik: "TR-34-99-41-2021",
              Cinsiyet: "disi"
            },
            {
              id: "54",
              name: "boz",
              bilezik: "TR-34-99-44-2021",
              Cinsiyet: "disi"
            },
            {
              id: "108",
              name: "ananas",
              bilezik: "TR-34-99-98-2021",
              Cinsiyet: "erkek"
            },
            {
              id: "121",
              name: "apdi",
              bilezik: "TR-34-99-111-2021",
              Cinsiyet: "disi"
            }
          ]
        }
      ]
    },
    {
      id: "6",
      name: "askim",
      bilezik: "TR-34-99-6-2020",
      Cinsiyet: "erkek",
      children: [
        {
          id: "73",
          name: "firfir",
          bilezik: "TR-34-99-63-2021",
          Cinsiyet: "disi"
        },
        {
          id: "93",
          name: "kartopu",
          bilezik: "TR-34-99-83-2021",
          Cinsiyet: "erkek"
        },
        {
          id: "140",
          name: "aksak",
          bilezik: "TR-34-99-5-2022",
          Cinsiyet: "erkek"
        },
        {
          id: "144",
          name: "kartopu",
          bilezik: "TR-34-99-9-2022",
          Cinsiyet: "disi"
        },
        {
          id: "177",
          name: "alicik",
          bilezik: "TR-34-99-42-2022",
          Cinsiyet: "erkek"
        }
      ]
    },
    {
      id: "7",
      name: "aygiz",
      bilezik: "TR-34-99-7-2020",
      Cinsiyet: "disi",
      children: [
        {
          id: "52",
          name: "cansin",
          bilezik: "TR-34-99-42-2021",
          Cinsiyet: "disi"
        },
        {
          id: "82",
          name: "aristo",
          bilezik: "TR-34-99-72-2021",
          Cinsiyet: "disi"
        },
        {
          id: "134",
          name: "taklaci",
          bilezik: "TR-34-99-124-2021",
          Cinsiyet: "erkek"
        },
        {
          id: "141",
          name: "asma",
          bilezik: "TR-34-99-6-2022",
          Cinsiyet: "disi"
        },
        {
          id: "149",
          name: "baskan",
          bilezik: "TR-34-99-14-2022",
          Cinsiyet: "disi"
        }
      ]
    }
  ]
};

export default {
  data() {
    this.chartSettings = {
      seriesMap: {
        tree1: {
          left: "5%",
          right: "2%",
          top: "19%",
          bottom: "20%",

          symbol: "emptyCircle",
          symbolSize: 16,
          orient: "vertical",

          expandAndCollapse: true,

          label: {
            position: "top",
            rotate: -90,
            verticalAlign: "middle",
            align: "right",
            fontSize: 18
          },

          leaves: {
            label: {
              position: "bottom",
              rotate: -90,
              verticalAlign: "middle",
              align: "left"
            }
          },

          animationDurationUpdate: 750
        }
      }
    };
    return {
      chartData: {
        columns: ["name", "value"],
        rows: [
          {
            name: "tree1",
            value: [treeData]
          }
        ]
      }
    };
  }
};
</script>