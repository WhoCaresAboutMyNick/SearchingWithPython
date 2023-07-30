import customtkinter
import webbrowser

ctk = customtkinter

buttonClicked = False

web = webbrowser


def whenClicked():
    search = entry.get()
    web.open('https://google.com/search?q=' + search)


ctk.set_appearance_mode("dark")
ctk.set_default_color_theme("dark-blue")

root = ctk.CTk()
root.geometry("500x350")

frame = ctk.CTkFrame(master=root)
frame.pack(pady=20, padx=60, fill="both", expand=True)

label = ctk.CTkLabel(master=frame, text="Search")
label.pack(pady=10, padx=10)

entry = ctk.CTkEntry(master=frame, placeholder_text="Query")
entry.pack(pady=10, padx=10)

button = ctk.CTkButton(master=frame, text="Search", command=whenClicked)
button.pack(pady=10, padx=10)

root.mainloop()
