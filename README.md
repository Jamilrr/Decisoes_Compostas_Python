# Decisoes_Compostas_Python
nome=input("Digite o nome: ") <br>
idade=int(input("Digite a idade: ")) <br>
doenca_infectocontagiosa=input("Suspeita de doença infecto-contagiosa?").upper() <br>
if idade>=65 and doenca_infectocontagiosa=="SIM":
    print("O paciente será direcionado para sala AMARELA - COM prioridade") <br>
elif idade < 65 and doenca_infectocontagiosa == "SIM":
    print("O paciente será direcionado para sala AMARELA - SEM prioridade") <br>
elif idade >= 65 and doenca_infectocontagiosa == "NAO":
    print("O paciente será direcionado para sala BRANCA - COM prioridade") <br>
elif idade < 65 and doenca_infectocontagiosa == "NAO":
    print("O paciente será direcionado para sala BRANCA - SEM prioridade") <br>
else:
    print("Responda a suspeita de doença infectocontagiosa com SIM ou NAO") <br>
