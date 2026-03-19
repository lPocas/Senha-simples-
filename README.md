# Senha-simples-

int main() {

    std::cout << "Try programiz.pro\n";

    int senha = 0;

    if  (senha != 2026) {
        std::cout << "Digite a senha: ";
        std::cin >> senha;

        if (senha != 2026) {
            std::cout << "Senha invalida\n";
        }
    }

    std::cout << "Acesso liberado";

    return 0;
