def calcular_soma_e_media(lista):
    """
    Calcula a soma e a média de uma lista de números.

    Args:
    - lista: uma lista de números.

    Returns:
    - soma: a soma dos números na lista.
    - media: a média dos números na lista.
    """
    soma = sum(lista)
    media = soma / len(lista)
    return soma, media

def substituir_palavra(lista, palavra_procurada, nova_palavra):
    """
    Substitui as ocorrências de uma palavra por outra em uma lista de palavras.

    Args:
    - lista: uma lista de palavras.
    - palavra_procurada: a palavra que será substituída.
    - nova_palavra: a palavra que substituirá a palavra_procurada.

    Returns:
    - lista_alterada: a lista com as substituições feitas.
    """
    lista_alterada = [nova_palavra if palavra == palavra_procurada else palavra for palavra in lista]
    return lista_alterada

def gerar_triangulo(num_linhas):
    """
    Gera um triângulo de asteriscos para o número de linhas informado.

    Args:
    - num_linhas: o número de linhas do triângulo.

    Prints:
    - O triângulo de asteriscos.
    """
    for i in range(1, num_linhas + 1):
        print('*' * i)

# Testando as funções
if __name__ == "__main__":
    # Testando a função calcular_soma_e_media
    lista_numeros = [1, 2, 3, 4]
    soma, media = calcular_soma_e_media(lista_numeros)
    print("Soma:", soma)
    print("Média:", media)

    # Testando a função substituir_palavra
    lista_palavras = ["banana", "morango", "limão"]
    palavra_procurada = "limão"
    nova_palavra = "laranja"
    lista_alterada = substituir_palavra(lista_palavras, palavra_procurada, nova_palavra)
    print("Lista alterada:", lista_alterada)

    # Testando a função gerar_triangulo
    num_linhas = 4
    print("Triângulo de asteriscos:")
    gerar_triangulo(num_linhas)
