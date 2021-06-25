<template>
  <div>
    <DetailBlog :blog="blog" />
  </div>
</template>

<script>
// @ is an alias to /src
import DetailBlog from "@/components/uncommon/Blogs/DetailBlog.vue";

export default {
  name: "Detail",
  components: {
    DetailBlog,
  },
  data() {
    return {
      blogs: [
        {
          createdAt: 1624608139,
          thumbnail: "http://placeimg.com/640/480/fashion",
          title: "Investor Creative Producer",
          author: "Dr. Regina Reichert",
          content:
            "Aliquam dolor eius ab rem illum eos ipsum expedita. Dolor et ad explicabo nobis et alias possimus enim. Voluptatum delectus nulla adipisci dolores. Cumque sit id sapiente repudiandae nobis debitis.",
          description:
            "Qui culpa eius quis a aliquid reiciendis ut sequi. Quidem ut omnis debitis fugit perspiciatis neque excepturi. Eius ipsum adipisci id odit esse nesciunt modi facilis est. Ut et sequi repellat voluptatem magni. Libero ut aperiam quod sed sit perferendis rerum ut et. Accusamus laudantium consequatur facere.\n \rQuam velit saepe labore consequuntur laborum qui omnis eos quis. Fugit dolor quasi aut harum soluta tenetur. Sed soluta rerum sapiente quisquam. Neque blanditiis eum ratione. Sit quia libero.\n \rAutem accusantium expedita ab dolor laboriosam. Sit modi beatae corporis maxime. Eos temporibus ex aliquam necessitatibus consequatur vitae reprehenderit pariatur adipisci. Ut architecto natus non consectetur.",
          tag: [],
          id: "1",
        },
        {
          createdAt: 1624608079,
          thumbnail: "http://placeimg.com/640/480/city",
          title: "Principal Functionality Assistant",
          author: "Rosie Emard",
          content:
            "Quo ducimus voluptatibus similique vel in. Sit quaerat sunt quibusdam quae laudantium. At ut doloremque voluptas earum. Ut minus non facere explicabo. Sit ea ad fugit qui at quibusdam dolores magnam veniam. Veritatis perferendis tempore fugit voluptatum esse.",
          description:
            "Facilis ducimus velit totam natus eum. Excepturi voluptatibus non unde possimus sit laborum ut officia voluptatem. Dolorem atque quia soluta ut odio maiores distinctio explicabo rerum.\n \rDucimus voluptatibus aspernatur laboriosam et aut eos. Ea provident voluptatem sed necessitatibus. Quo mollitia corrupti aliquam eligendi. Corrupti ex repellendus quae et molestiae qui odio possimus. Laboriosam ut delectus nihil porro quis omnis.\n \rVoluptas eum quo maiores. Explicabo aut et. Tempora amet et est repudiandae qui vel. Quaerat qui dolorem molestias. Atque et qui quam dolor suscipit eos.",
          tag: [],
          id: "2",
        },
        {
          createdAt: 1624608019,
          thumbnail: "http://placeimg.com/640/480/business",
          title: "Dynamic Usability Architect",
          author: "Kellie Muller PhD",
          content:
            "Debitis cumque eos ipsa ratione ex alias vel. Incidunt ipsum tempora beatae est. Exercitationem et vitae sequi quidem enim sint laudantium iure. Est provident sit doloribus. Cumque unde ut sit neque. Voluptates labore veritatis iusto et ea eos quibusdam.",
          description:
            "Iure accusamus voluptas esse. Dolor voluptas nihil quasi qui magnam. Error laborum quia atque. Accusamus rerum nemo cupiditate earum libero repudiandae et placeat magnam. In unde voluptates vel deserunt.\n \rQuibusdam provident natus nihil. Corrupti deserunt perferendis mollitia. Non sunt assumenda est culpa nemo in. Libero voluptatem nisi ea similique numquam dolores et mollitia. Laborum architecto optio ut et soluta soluta itaque minima.\n \rMaiores quae qui aliquam. Explicabo quisquam ullam similique voluptatem repudiandae odio eaque veritatis. Consectetur repudiandae optio cumque impedit et. Ut deserunt cum sunt labore praesentium delectus. Nisi incidunt explicabo. Reiciendis quia laboriosam magni ea.",
          tag: [],
          id: "3",
        },
        {
          createdAt: 1624607959,
          thumbnail: "http://placeimg.com/640/480/city",
          title: "Corporate Data Officer",
          author: "Jimmie Gottlieb",
          content:
            "A dolores adipisci assumenda velit illo fugiat ut velit assumenda. Dolorem unde sequi autem nemo. Inventore tenetur corporis tempora repellendus ut delectus. Recusandae et quo. Officiis vero dolorum vero. Ullam aut et.",
          description:
            "Cum quisquam voluptatum quam. Ad quos quo asperiores dolorem mollitia sapiente accusamus. Vel temporibus autem possimus unde accusantium. Consectetur ut fuga quia rerum vel rem consequatur. Dolor voluptatum aut aut est omnis nihil deleniti. Nemo quod dolorem modi.\n \rEt veritatis voluptatum dolorum numquam culpa aperiam. Et aspernatur et modi sit. Quia esse laudantium sint quia quia ab qui iusto. Exercitationem quidem sequi. Ullam repellendus ipsa magni sit dolores molestias. Repellat placeat et nostrum quia eos provident qui itaque nam.\n \rPossimus est qui recusandae eligendi ad ab occaecati qui. Dignissimos ut sint. Ad esse corrupti sit vel dolorem rem non repudiandae. Consequatur omnis suscipit ut cumque esse non et veritatis eos. Impedit sint eligendi voluptates reiciendis non eveniet. Aspernatur inventore reprehenderit sequi qui voluptatum provident rem blanditiis nisi.",
          tag: [],
          id: "4",
        },
        {
          createdAt: 1624607899,
          thumbnail: "http://placeimg.com/640/480/food",
          title: "Principal Marketing Developer",
          author: "Howard Ward",
          content:
            "Debitis et accusamus fuga. A asperiores nostrum ut dolor. Atque sit ipsam qui provident et voluptatem.",
          description:
            "Atque sequi dolorum optio. Optio excepturi quas laboriosam quae. Illo est quia dignissimos praesentium dolorum doloremque nihil tenetur. Odit esse nam non. Voluptatem in et magnam sapiente illum. Voluptas consequatur est suscipit aliquid enim.\n \rNisi fugiat illum. Omnis cum dolores facilis qui quia. Vero explicabo aut tempora nam rem fugit est. Recusandae omnis ducimus sequi eos qui aut illum est. Nobis aut temporibus unde praesentium.\n \rPorro sint ut aspernatur reiciendis odio omnis nostrum suscipit alias. Harum itaque ratione mollitia. Dolorem eligendi quasi corporis quia quia.",
          tag: [],
          id: "5",
        },
        {
          createdAt: 1624607839,
          thumbnail: "http://placeimg.com/640/480/fashion",
          title: "District Research Agent",
          author: "Francis Hirthe",
          content:
            "Provident velit ab saepe hic veritatis dolor. Corporis aut sunt exercitationem harum ut nemo. Totam vero unde perspiciatis sapiente sunt. Dolorem amet numquam cupiditate. Atque accusantium ex ut itaque. Cum repellendus dolor delectus voluptas ut ut eum enim.",
          description:
            "Harum incidunt dolores et nihil repellat aut. Rerum commodi eaque aut. Explicabo omnis dolorem quidem non necessitatibus expedita porro eum quia.\n \rUt et laborum laborum quos est veniam ut aliquam. Quo ut aspernatur dolor perferendis. Earum in delectus a. Voluptatem labore et sint.\n \rQui et qui natus assumenda molestiae nobis. Ad voluptatem ipsam neque autem unde beatae. Fugiat provident molestiae iusto itaque beatae molestiae necessitatibus. Aspernatur eveniet culpa accusamus facere et reprehenderit. Ullam tempore iusto cupiditate. Eum eos fuga.",
          tag: [],
          id: "6",
        },
        {
          createdAt: 1624607779,
          thumbnail: "http://placeimg.com/640/480/city",
          title: "Direct Division Specialist",
          author: "Roberto Pacocha DDS",
          content:
            "Commodi vel labore non at eos sed ut numquam veniam. Perferendis nisi vero nihil est nemo nam quas dolores. Iure modi vero distinctio cupiditate omnis placeat. Eos non culpa voluptas corrupti officiis et doloremque.",
          description:
            "Animi maxime at quia ipsa incidunt sit id explicabo quia. Dolorem quia tempore vitae veritatis qui ut impedit. Esse magni animi temporibus adipisci enim rem sint minima. Repellendus architecto qui tempore numquam voluptas. Quisquam et ducimus optio quas. Et ullam quia quos neque minus perferendis.\n \rVoluptatibus quis officia suscipit. Corporis voluptatibus voluptates voluptatibus consequuntur. Repellendus sapiente eum iure in dolorem voluptas incidunt.\n \rEt consectetur officia similique reiciendis ex perspiciatis. Animi repellendus et voluptas nihil eum. Et aut nobis reiciendis repellat. Quod ratione tempore in perferendis debitis voluptatem ipsam quam. Harum in eius non sed aliquam eius fugit aspernatur dolore. Et voluptas alias sunt saepe aut perferendis officiis sint accusamus.",
          tag: [],
          id: "7",
        },
        {
          createdAt: 1624607719,
          thumbnail: "http://placeimg.com/640/480/nature",
          title: "Senior Response Analyst",
          author: "Timmy Gaylord",
          content:
            "Et ea qui. Eum minus dolores impedit dolorum et fuga rerum. Impedit ex cum ad omnis. Sunt sint aliquam pariatur assumenda non veritatis et aperiam. Earum sapiente voluptate ut. Quis et autem adipisci et voluptas.",
          description:
            "Quo error et ex sed veritatis quo. Accusantium deleniti praesentium numquam. Sequi quas est. Nulla itaque assumenda qui natus vel. Sint voluptas eveniet.\n \rMolestiae numquam doloribus molestiae aut in voluptas ex. Ut perspiciatis saepe quod voluptas nulla. Cupiditate praesentium quia voluptas doloribus alias repudiandae blanditiis. Magnam ducimus laudantium possimus tempore error rerum quas corrupti. Sed occaecati nihil harum nobis corporis veritatis repellat qui officiis. Quo rerum optio laboriosam veniam numquam.\n \rMolestias voluptates nostrum nulla dolorem consequuntur minima itaque distinctio dicta. Occaecati nemo qui aspernatur consequatur voluptatum quia commodi veniam. Corrupti quia et perspiciatis perferendis voluptatibus voluptatibus sed. Et explicabo numquam eaque eligendi earum. Id necessitatibus et deleniti sapiente. Corporis et veniam.",
          tag: [],
          id: "8",
        },
        {
          createdAt: 1624607659,
          thumbnail: "http://placeimg.com/640/480/nature",
          title: "Dynamic Interactions Developer",
          author: "Amos Champlin PhD",
          content:
            "Corporis hic nulla odit quia provident. Id quas dolorum laborum. Ea voluptatem voluptate provident eaque sed est labore.",
          description:
            "Consequuntur harum consequatur cumque enim molestias et impedit. Aliquam ut modi quod saepe aliquam inventore iure. Incidunt omnis explicabo harum suscipit quibusdam. Reiciendis doloremque facere earum officiis consequatur ratione vel non explicabo. Sit eveniet praesentium at enim a. Illo labore quae consequatur aut.\n \rLaboriosam voluptatibus odit alias velit ut provident aliquam ad. Nesciunt quisquam quisquam. Dolorem minima assumenda. Aut at libero natus porro sunt nihil atque. Rerum delectus tempora ut laboriosam rerum et amet suscipit provident. Sit cumque necessitatibus tempora.\n \rQui soluta aliquam voluptas illo. Nostrum officia nostrum libero hic earum assumenda consequatur. Et velit nisi. Eum nostrum aut est et quaerat ad ut sed. Architecto vitae totam doloremque et ut eos laudantium.",
          tag: [],
          id: "9",
        },
        {
          createdAt: 1624607599,
          thumbnail: "http://placeimg.com/640/480/nature",
          title: "Principal Data Consultant",
          author: "Ms. Jane Koch",
          content:
            "Commodi tempore natus quaerat reiciendis. Molestias delectus consequatur impedit cupiditate sunt nesciunt cumque ea. Magnam et est et architecto tenetur et voluptatum aut molestiae. Et quos mollitia rerum quia. Tempora voluptatem rerum deleniti voluptate. Recusandae voluptas consectetur voluptas eligendi aut et ipsam voluptas.",
          description:
            "Tempore reprehenderit architecto et ab vitae optio culpa. Excepturi consectetur aperiam ipsam veritatis. Nemo quaerat molestias corporis enim alias vel voluptatem. At earum inventore dolorem accusamus beatae. Dolor id ipsum molestias et sint soluta soluta reiciendis.\n \rItaque quidem perspiciatis omnis. Occaecati quia omnis. Aut sequi odio. Fugit quibusdam et ullam. Et nostrum rem error ut provident vel.\n \rAccusantium dolores ut facere. Dolores quam qui. Vel sit possimus ea odio excepturi esse esse.",
          tag: [],
          id: "10",
        },
      ],
      active_blog: {},
    };
  },
  created() {
    alert(this.$route.params.id);
  },
  computed: {
    blog() {
      this.blogs.forEach((blog) => {
        if (blog.id === this.$route.params.id) {
          this.active_blog = blog;
        }
      });
      return this.active_blog ;
    },
  },
};
</script>
