# NoiseDaddy

**NoiseDaddy** is a chaotic little microphone prank tool that reacts to loud noises, slaps, or claps by playing a sound—by default, `yes_daddy.wav`.  

It’s simple, fun, and slightly mischievous.

---

## How It Works

- Listens to your microphone in real-time.  
- Detects sudden **spikes in volume** (like slaps, claps, or yelling).  
- Plays the sound file instantly when a spike is detected.  

**Pro tip:** it ignores normal speech unless it’s very loud.

---

## Features

- Real-time noise spike detection  
- Plays a sound when sudden spikes(claps, slaps, loud sound) are detected  
- Fun and mischievous  
- Custom sound support  

---

## Usage

1. Place `noise_dad.exe` and `yes_daddy.wav` in the same folder.  
2. Run `noise_dad.exe`.  
3. Clap, slap, or yell near your microphone… enjoy the reaction!  

### Change the Sound

You can swap `yes_daddy.wav` with any `.wav` file:

1. Place your `.wav` file in the same folder as the `.exe`.  
2. Rename it exactly to `yes_daddy.wav`.  
3. Run `noise_dad.exe` and your custom sound will play instead.

### CLI Usage

- Run cmd in the same dir,
  ```bash
  # Multiplier < 6.0 (sensitive) and becomes hard on the other side > 6.0
  noise_dad --multiplier 0.6

  # CoolDown after sound
  noise_dad --cooldown 1.0 

  # custom sound
  noise_dad --sound #path to sound
  ```

---

## Tips

- Keep a small **cooldown** between triggers to avoid chaos in crowded rooms.  
- Works best on **laptop microphones or USB mics**.  
- Adjust your distance for perfect prank effect.  

---

## Why It’s Fun

- Perfect for **office pranks** or **Discord/voice chat trolling**  
- Makes even quiet environments a little unpredictable  
- A lightweight, portable prank you can run anywhere  

---

## License

Apache 2.0 License — use it, prank responsibly, and have fun!  

---

**Get ready… the mic fights back. 😏**
