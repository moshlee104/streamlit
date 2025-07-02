import streamlit as st

st.title("💬 Text Reverser")

user_input = st.text_input("Enter some text:")
if user_input:
    st.write("Reversed:", user_input[::-1])
