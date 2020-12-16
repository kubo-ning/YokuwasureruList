## 週の初めにする処理
Dim s = ConvertWorkDayStart8(_date)
		Dim ret = s.AddDays(DayOfWeek.Monday - s.DayOfWeek)

		Return ret
