# Digital-frequency-meter
# Digital Frequency Meter

print("==============================")
print("       DIGITAL FREQUENCY METER")
print("==============================")

frequency = float(input("Enter frequency signal (Hz): "))

print("\n------------------------------")
print("Measured Frequency:", frequency, "Hz")
print("------------------------------")

if frequency <= 0:
    print("⚠️ Invalid frequency")
elif frequency < 49:
    print("🔴 Low Frequency")
elif frequency > 51:
    print("🔴 High Frequency")
else:
    print("🟢 Frequency is Normal")

print("\nMeasurement Completed")
