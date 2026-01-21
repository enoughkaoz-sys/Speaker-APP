import type { ExpoConfig } from "expo/config";

const config: ExpoConfig = {
  name: "Speaker",
  slug: "speaker-app",
  scheme: "speaker",
  version: "0.2.0",
  orientation: "portrait",
  userInterfaceStyle: "automatic",
  newArchEnabled: true,
  platforms: ["android", "ios"],
  icon: "./assets/icon.png",
  splash: {
    image: "./assets/splash.png",
    resizeMode: "contain",
    backgroundColor: "#0B0B0F",
  },
  updates: {
    fallbackToCacheTimeout: 0,
  },
  assetBundlePatterns: ["**/*"],
  android: {
    package: "bar.speaker.app",
    adaptiveIcon: {
      foregroundImage: "./assets/adaptive-icon.png",
      backgroundColor: "#0B0B0F",
    },
  },
  plugins: [
    "expo-router",
  ],
};

export default config;
