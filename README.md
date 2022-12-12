//Завдання 4. Користувач вводить з клавіатури час у секундах, що минув з початку дня.Вивести на екран поточний
	//час у годинах, хвилинах і секундах.

	int sec;
	cout << " Enter the number of seconds that have passed since the beginning of the day:  " << endl;
	cin >> sec;
	cout << "Current time in hours:  " <<(sec+0)/3600 << endl;
	cout << "Current time in minuter:  " <<(sec + 0)/60 << endl;
	cout << "Current time in seconds:  " << sec + 0 << endl;
