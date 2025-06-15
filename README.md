ໂຄງສ້າງໂປຣແກຣມ
gis-cadastral/
├── client/                  # ສ່ວນ Frontend (Vue.js)
│   ├── public/             # ໄຟລ໌ສະຖິຕິ
│   ├── src/
│   │   ├── assets/         # ຮູບພາບ ແລະ ໄຟລ໌ CSS
│   │   ├── components/     # ຄອມໂປເນັນຕ່າງໆ
│   │   │   ├── auth/       # ຄອມໂປເນັນການເຂົ້າສູ່ລະບົບ
│   │   │   ├── gis/        # ຄອມໂປເນັນ GIS
│   │   │   ├── layout/     # ຄອມໂປເນັນໂຄງສ້າງໜ້າເວັບ
│   │   │   └── ui/         # ຄອມໂປເນັນ UI ທົ່ວໄປ
│   │   ├── composables/    # Vue Composables
│   │   ├── router/         # ການຕັ້ງຄ່າເສັ້ນທາງ
│   │   ├── stores/         # Pinia stores
│   │   ├── utils/          # ຟັງຊັນຊ່ວຍ
│   │   ├── views/          # ໜ້າເວັບຕ່າງໆ
│   │   ├── App.vue         # ຄອມໂປເນັນຫຼັກ
│   │   └── main.js         # ຈຸດເລີ່ມຕົ້ນ Vue
│   ├── package.json
│   └── vite.config.js      # ການຕັ້ງຄ່າ Vite
│
├── server/                 # ສ່ວນ Backend (Node.js/Express)
│   ├── config/            # ການຕັ້ງຄ່າ
│   ├── controllers/       # ຕົວຄວບຄຸມ
│   ├── middlewares/       # ຕົວກວດສອບ
│   ├── models/           # ໂມດິວຂໍ້ມູນ
│   ├── routes/           # ເສັ້ນທາງ API
│   ├── services/         # ບໍລິການຕ່າງໆ
│   ├── app.js           # ໂປຣແກຣມຫຼັກ
│   └── package.json
│
├── geoserver/            # ການຕັ້ງຄ່າ GeoServer
│   ├── data_dir/        # ໂຟນເດີຂໍ້ມູນ GeoServer
│   └── dockerfile       # ຄຳສັ່ງຕິດຕັ້ງ GeoServer
│
├── docker-compose.yml    # ຄຳສັ່ງ Docker ສຳຫຼັບລະບົບ
└── README.md            # ຄຳແນະນຳການຕິດຕັ້ງ
