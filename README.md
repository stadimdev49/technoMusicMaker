🎧 Techno Beat Studio & Sequencer — Οδηγός Χρήσης & Τεκμηρίωση (README)

Το Techno Beat Studio είναι ένα πλήρες, διαδραστικό διαδικτυακό περιβάλλον παραγωγής techno μουσικής (Digital Audio Workstation / Drum Machine / Acid Synth) που λειτουργεί απευθείας στον περιηγητή (browser) χωρίς να απαιτεί εγκατάσταση εξωτερικών προγραμμάτων.
🚀 Χαρακτηριστικά & Δυνατότητες
1. Μηχανή Συνθετητή & Δειγματοληψίας (Audio Engine)

    9 Ξεχωριστά Κανάλια Ήχου:

        Kick: 909 Heavy Techno, Industrial Distortion, Punchy Club Kick.

        Sub Rumble: Sub Bass Kick Glue, Metallic Tail, Offbeat Driving Sub.

        Closed Hi-Hat & Open Hi-Hat: 909 Crisp, Metallic Industrial, Minimal Analog Hats.

        Snare / Clap: Punchy Snare, Industrial Clap, Noise Rim.

        Toms (Low/Mid): FM Deep Tom, Industrial Perc, Electro Accent.

        Synth Stab: Rave Chords, Detroit Synth, Deep Chord.

        Acid 303: TB-303 Synthesizer emulator (Sawtooth & Square waveforms).

        Noise FX: Laser FX, Sub Drop, White Noise Sweep.

    Master FX Rack:

        Overdrive Distortion: Προσθέτει ζεστασιά ή βιομηχανική παραμόρφωση (Industrial saturation).

        Master Lowpass Filter: Cutoff Sweep για breakdowns & buildups.

        Reverb & Delay: Εφέ αντήχησης και καθυστέρησης με ξεχωριστά ρυθμιστικά στάθμης.

        Sidechain Compression: Δυναμικό "ducking" των υπόλοιπων οργάνων πάνω στο Kick για το κλασικό techno pumping effect.

2. Step Sequencer & Timing

    Επιλογή Βημάτων (Length): 16, 32 ή 64 steps για πολύπλοκες και εξελιγμένες συνθέσεις.

    Swing / Shuffle: Ρύθμιση ρυθμικού «λικνίσματος» (0% - 75%).

    BPM Control & Tap Tempo: Εύρος ρυθμού από 60 έως 180 BPM με δυνατότητα Tap Tempo.

    Pattern Banks (A / B / C / D): 4 ανεξάρτητες τράπεζες μοτίβων για ζωντανή εναλλαγή (Live Performance).

3. Presets & Διαχείριση Αρχείων

    Προεγκατεστημένα Techno Sub-genres:

        🔴 Peak Time Techno: 132 BPM – Heavy Kicks & Driving Hi-Hats.

        ⚡ Dark Industrial: 140 BPM – Raw Distorted Bass & Harsh Claps.

        ☣️ Acid Rave 303: 135 BPM – Dynamic TB-303 Sweeps & Glitchy Percussion.

        🌊 Dub Minimal: 126 BPM – Deep Atmosphere & Subtle Grooves.

        🌌 Melodic Techno: 124 BPM – Emotional Synth Stabs & Atmospheric FX.

        ⚡ Schranz / Hardtechno: 150 BPM – Extreme Distortion & Fast BPM.

    Εξαγωγή & Εισαγωγή JSON: Αποθήκευση και φόρτωση ολόκληρων των μοτίβων σας σε αρχεία .json.

    WAV Audio Recorder: Απευθείας εγγραφή της εξόδου ήχου σε ασυμπίεστο αρχείο .wav (16-bit PCM) και αυτόματη λήψη στον υπολογιστή/κινητό.

🛠️ Τεχνικές Προδιαγραφές & Αρχιτεκτονική

    Web Audio API: Όλοι οι ήχοι δημιουργούνται σε πραγματικό χρόνο (Real-time DSP synthesis & Buffer processing) χωρίς εξωτερικά δείγματα (no external sample dependencies).

    WAV Encoder (PCM 16-bit): Ενσωματωμένη μηχανή εγγραφής σε JavaScript που επεξεργάζεται τα raw audio floats και παράγει έγκυρες κεφαλίδες (RIFF WAV headers) για 100% συμβατότητα με όλες τις συσκευές.

    HTML5 Canvas Visualizer: Ζωντανός παλμογράφος (Oscilloscope / Spectrum Analyzer) για οπτική αναπαράσταση της κυματομορφής.

📖 Οδηγίες Χρήσης (Quick Start)

    Έναρξη Αναπαραγωγής: Πατήστε το κουμπί ▶ Play / Stop (ή το πλήκτρο Space στο πληκτρολόγιο).

    Δημιουργία Rhythms: Πατήστε πάνω στα κουτάκια του Sequencer Grid για να ενεργοποιήσετε/απενεργοποιήσετε βήματα.

    Ρύθμιση Acid 303: Χρησιμοποιήστε τα χειριστήρια Cutoff, Resonance, Decay και LFO στην ενότητα Acid 303 Synthesizer για να διαμορφώσετε τον acid ήχο.

    Εγγραφή σε WAV:

        Πατήστε το κουμπί 🔴 Εγγραφή.

        Αφήστε το κομμάτι να παίξει για όση διάρκεια επιθυμείτε.

        Πατήστε ⏹ Διακοπή Εγγραφής.

        Το αρχείο .wav θα μεταφορτωθεί αυτόματα στο φάκελο Λήψεις (Downloads) της συσκευής σας, ενώ εμφανίζεται και το πράσινο κουμπί «Κατέβασμα Αρχείου (.wav)» για χειροκίνητη λήψη.
