class KavyaSingh:
    """
    🎯 Data Analyst based in Noida, India.
    🔍 Obsessed with the gap between raw data and real decisions.
    💡 Turning chaos into clarity, one dataset at a time.
    """

    def __init__(self):
        self.role        = "📊 Data Analyst"
        self.location    = "📍 Noida, India 🇮🇳"
        self.focus       = [
            "🤖 Machine Learning & Predictive Modeling",
            "🧠 Generative AI & Prompt Architecture",
            "📈 Data Visualization & Storytelling",
            "🔮 Business Intelligence & Strategy",
        ]
        self.currently   = "🚀 Deepening Python + Machine Learning"
        self.stack       = {
            "languages" : ["🐍 Python", "🗄️ SQL"],
            "ml_stack"  : ["🐼 Pandas", "🔢 NumPy"],
            "viz"       : ["📊 Power BI", "📉 Tableau"],
            "ai"        : ["🎯 Prompt Engineering", "✨ Generative AI"],
        }
        self.superpower  = "🦸‍♀️ Turning data into decisions"
        self.motto       = "📌 In God we trust, all others must bring data."

    def prompt_philosophy(self) -> str:
        return (
            "💬 Good analysts don't just report numbers — "
            "they uncover the stories behind them. 📖✨"
        )

    def introduce(self) -> str:
        return (
            f"\n👋 Hey there! I'm {self.role} from {self.location}\n"
            f"🚀 Currently: {self.currently}\n"
            f"💪 Superpower: {self.superpower}\n"
            f"🎯 Motto: {self.motto}\n"
        )

    def show_stack(self) -> str:
        stack_str = "\n🛠️ My Tech Stack:\n" + "-" * 30 + "\n"
        for category, tools in self.stack.items():
            stack_str += f"\n📁 {category.upper()}: {', '.join(tools)}"
        return stack_str

# 🚀 Creating the data wizard
Kavya = KavyaSingh()

# 🌟 Let's see the magic unfold
print("=" * 50)
print("🌟 KAVYA SINGH — DATA ANALYST EXTRAORDINAIRE 🌟")
print("=" * 50)

print(Kavya.introduce())
print(Kavya.prompt_philosophy())
print("\n" + "=" * 50)
print(Kavya.show_stack())
print("\n" + "=" * 50)
print("🔥 Ready to decode the matrix! Let's go! 🚀")
print("=" * 50)
