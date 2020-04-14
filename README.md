    public void filterAnimalsByValue(String value, ArrayList<Animal> animalArray) {
        for (int i = 0; i < animalArray.size(); i++) {
            Animal tempAnimal = animalArray.get(i);

            }
            if (activeKey.equals("type")) {
                if (!tempAnimal.getType().equals(value)) {
                    tempAnimal.setDoShow(false);
                }
                continue;
            }
            if (activeKey.equals("lifestage")) {
                if (!tempAnimal.getLifeStage().equals(value)) {
                    tempAnimal.setDoShow(false);
                }
                continue;
            }
            if (activeKey.equals("sex")) {
                if (!tempAnimal.getSex().equals(value)) {
                    tempAnimal.setDoShow(false);
                }
                continue;
            }
            if (activeKey.equals("condition")) {
                if (!tempAnimal.getCondition().equals(value)) {
                    tempAnimal.setDoShow(false);
                }
                continue;
            }
            if (activeKey.equals("environment")) {
                if (!tempAnimal.getEnvironment().equals(value)) {
                    tempAnimal.setDoShow(false);
                }
                continue;
            }
        }
    }
      
}
