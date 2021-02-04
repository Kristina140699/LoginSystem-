from tkinter import *
from PIL import ImageTk
from tkinter import messagebox
class Login_System:
	def __init__(self,root):
		self.root = root
		self.root.title("LOGIN SYSTEM | Kristina Barooah")
		self.root.geometry("1350x700+0+0")

		self.phone_image=PhotoImage(file="images/phoneFinal1.png")
		self.lbl_Phone_image=Label(self.root,image=self.phone_image).place(x=200,y=90)

		login_frame=Frame(self.root,bd=2,relief=RIDGE)
		login_frame.place(x=650,y=90,width=350,height=460)

		title=Label(login_frame,text="LOGIN SYSTEM",font=("Elephant",25,"bold"),bg="white").place(x=0,y=30,relwidth=1)

		lbl_user=Label(login_frame,text="Username",font=("Andalus",15),bg="white",fg="#767171").place(x=50,y=100)
		txt_user=Entry(login_frame,font=("Andalus",15),bg="#ECECEC").place(x=50,y=140)

		lbl_pass=Label(login_frame,text="Password",font=("Andalus",15),bg="white",fg="#767171").place(x=50,y=200)
		txt_pass=Entry(login_frame,font=("Andalus",15),bg="#ECECEC").place(x=50,y=240,width=250)

		btn_login=Button(login_frame,text="Log In",font=("Arial Rounded MT Bold",15),bg="#00B0F0",activebackground="#00B0F0",fg="white",activeforeground="white").place(x=50,y=300,width=250,height=35)

		hr=Label(login_frame,bg="lightgray").place(x=50,y=370,width=250,height=2)
		or_ = Label(login_frame,text="OR",bg="white",fg="black",font=("times new roman",15,"bold")).place(x=150,y=360)

		btn_forget=Button(login_frame,text="Forget Password?",font=("times new roman",13),bg="white",fg="#00759E",bd=0,activebackground="white",activeforeground="#00759E").place(x=100,y=390)

		register_frame = Frame(self.root,bd=2,relief=RIDGE,bg="white")
		register_frame.place(x=650,y=570,width=350,height=60)

		lbl_reg=Label(register_frame,text="Don't have an account?",font=("times new roman",13),bg="white").place(x=40,y=20)
		btn_signup=Button(register_frame,text="Sign Up!!",font=("times new roman",13,"bold"),bg="white",fg="#00759E",bd=0,activebackground="white",activeforeground="#00759E").place(x=200,y=17)


		self.im1=ImageTk.PhotoImage(file="images/image2.png")
		self.im2=ImageTk.PhotoImage(file="images/image3.png")
		self.im3=ImageTk.PhotoImage(file="images/image4.png")

		self.lbl_change_image=Label(self.root)
		self.lbl_change_image.place(x=240,y=50,width=370,height=662)

		self.animate()

	
	def animate(self):
		self.im=self.im1
		self.im1=self.im2
		self.im2=self.im3
		self.im3=self.im 
		self.lbl_change_image.config(image=self.im)
		self.lbl_change_image.after(2000,self.animate)       



root = Tk()
obj = Login_System(root)
root.mainloop()
