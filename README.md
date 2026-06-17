class KavyaSingh:
    """
    Data Analyst based in Noida, India.
    Obsessed with the gap between raw data and real decisions.
    """

    def __init__(self):
        self.role        = "Data Analyst"
        self.location    = "Noida, India 🇮🇳"
        self.focus       = [
            "Machine Learning & Predictive Modeling",
            "Generative AI & Prompt Architecture",
            "Data Visualization & Storytelling",
          
        ]
        self.currently   = "Deepening Python + Machine Learning"
        self.stack       = {
            "languages" : ["Python", "SQL"],
            "ml_stack"  : ["Pandas", "NumPy"],
            "viz"       : ["Power BI", "Tableau"],
             "ai"        : ["Prompt Engineering", "Generative AI"],
            
        }

    def prompt_philosophy(self) -> str:
        return (
            "Good analysts don't just report numbers"
            "they uncover the stories behind them."
        )


Kavya = KavyaSingh()
print(Kavya.prompt_philosophy())
