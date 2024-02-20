from aiogram.types import ReplyKeyboardMarkup, KeyboardButton

def get_kb() -> ReplyKeyboardMarkup:
    kb = ReplyKeyboardMarkup([
        [KeboardButton('Keyboard 1'), KeboardButton('Keyboard 2'), KeboardButton('Keyboard 3')],
        [KeboardButton('Keyboard 4'), KeboardButton('Keyboard 5'), KeboardButton('Keyboard 6')],
        [KeboardButton('Keyboard 7'),
    ])

    return kb
