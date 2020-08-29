# QML---Keys

//В корневом элементе обозначаем
Keys.enabled: true
Keys.priority: Keys.BeforeItem

//Далее описываем работу с кнопкой("Назад")
Rectangle(
	focus: true									//Фокус объекта внутри которого вызывается ивент кнопки обязательно должен быть true
	Keys.onPressed: {
		if (event.key == Qt.Key_Back) 			//Если нажата кнопка "Назад"
		{
			event.accepted = true 				//Ивент подтверждён
      
			//Далее описываем то что нам надо сделать при нажатии кнопки
      
		}
	}
}
