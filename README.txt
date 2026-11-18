MyPocketBudget Prototype 0.8.7 - Ocean Blue Selected Date Fix

- Restores chart layout, height, axis spacing, and proportions from v0.7.1.
- Keeps v0.8.0 daily details: select a bar/date to show daily totals and all transactions.
- Days without transactions explicitly show income 0.00 and expenses 0.00 baht.
- Compact month labels appear periodically (e.g. 1 พ.ย.) to keep 28–31 day charts readable.
- Retains localStorage key mypocket_v1 and all existing features: transactions, edit/delete,
  categories, budget, calendar, monthly/yearly reports, JSON backup/restore,
  Excel/CSV export, and print/PDF.
- Service worker cache updated to v0.8.4.

Back up JSON before replacing deployed files.

- v0.8.4: selected date uses dark Ocean Blue background with white text; empty days explicitly show zero income/expense and 'ไม่มีรายการในวันนี้'.

- v0.8.4: selected date label uses dark Ocean Blue with white text; removed native hover titles that could show a neighboring date; daily totals are recalculated from the selected date's transactions; empty days show zero totals and 'ไม่มีรายการในวันนี้'; improved spacing of the first abbreviated month label.

- v0.8.5: removes native floating browser tooltips from the daily chart; selected date styling, chart dimensions/colors, daily detail panel, data storage, and all existing features are unchanged.

- v0.8.7: fixes selected daily date label to show Ocean Blue background (#183B56) with white text. No chart geometry, colors, data, or other features changed.

- v0.8.7: fixes selected-day highlighting by matching the explicit numeric data-day attribute rather than parsing the accessible label. Chart dimensions, bar colors, data, and other functions are unchanged.
