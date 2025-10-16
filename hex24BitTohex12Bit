while True:
    hex24 = input("Enter 6-digit hex color: ").strip()
    if not hex24:
        break

    r = round(int(hex24[0:2], 16) / 255 * 15)
    g = round(int(hex24[2:4], 16) / 255 * 15)
    b = round(int(hex24[4:6], 16) / 255 * 15)

    hex12 = f"{r:X}{g:X}{b:X}"
    print(hex12)
