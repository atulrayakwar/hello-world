# hello-world
developing or printing....
app.use(bodyParser.urlencoded({ extended: false }));
app.use(bodyParser.json());
const port = 3001;
const sequelize = new Sequelize('test', 'root', 'root', {
    dialect: 'mysql',
    host :"localhost",
    port: 3306
  });
