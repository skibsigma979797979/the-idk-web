#include <SFML/Graphics.hpp>
#include <SFML/Window.hpp>

int main() {
    sf::RenderWindow window(sf::VideoMode(400, 200), "Button Example");

    sf::RectangleShape buttonHi(sf::Vector2f(100, 50));
    buttonHi.setFillColor(sf::Color::Green);
    buttonHi.setPosition(50, 75);

    sf::RectangleShape buttonBye(sf::Vector2f(100, 50));
    buttonBye.setFillColor(sf::Color::Red);
    buttonBye.setPosition(250, 75);

    while (window.isOpen()) {
        sf::Event event;
        while (window.pollEvent(event)) {
            if (event.type == sf::Event::Closed)
                window.close();
        }

        window.clear();
        window.draw(buttonHi);
        window.draw(buttonBye);
        window.display();
    }

    return 0;
}
