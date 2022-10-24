# turizmmalumotlari
import matplotlib.pyplot as plt

fig, ax = plt.subplots()

maqsadlar = ['Bo‘sh vaqt va dam olish', 'Davolanish', 'Qarindoshlarni yo‘qlash', 'O‘qish', 'Xizmat yuzasidan', 'Tijorat maqsadida' ]
soni = [155, 32, 250, 6, 60, 13]
bar_labels = ['red', 'blue', '_red', 'orange', '_blue', '_orange']
bar_colors = ['tab:red', 'tab:blue', 'tab:red', 'tab:orange', 'tab:blue', 'tab:orange']

ax.bar(maqsadlar, soni, label=bar_labels, color=bar_colors)

ax.set_ylabel('safar maqsadlari')



plt.show()
