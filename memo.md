service/todo.goの

type TODOService struct {
	db *sql.DB
}

を

type TODOService struct {
	DB *sql.DB
}

にした(大文字でないとmainパッケージからアクセスできないため)

どうすればいいか次の機会に聞いてみる