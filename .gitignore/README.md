# QuizApp
An android Quiz App that focuses on small children



had some issues uploading the commits. I'm not sure if i did things correctly

this is the XML

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"
        android:src="@drawable/kids1" />
    <ScrollView
        android:layout_width="wrap_content"
        android:layout_height="match_parent">
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_marginBottom="60dp"
            android:layout_marginLeft="30dp"
            android:layout_marginRight="30dp"
            android:layout_marginTop="30dp"
            android:background="#cc263238"
            android:focusable="true"
            android:focusableInTouchMode="true"
            android:orientation="vertical">
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:text="This is a quiz app for kids"
                android:textColor="#E1E1E1"
                android:textSize="16sp" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:text="What is your name?"
                android:textColor="#E1E1E1"
                android:textSize="32sp" />
            <EditText
                android:id="@+id/user_name_edit_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="16dp"
                android:hint="Click me and type your name :)"
                android:inputType="textCapWords"
                android:textColorHint="#E1E1E1" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:text="Question 1:   Are butterflies insects?"
                android:textColor="#E1E1E1"
                android:textSize="32sp" />
            <RadioGroup
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginBottom="16dp"
                android:orientation="vertical">
                <RadioButton
                    android:id="@+id/yes_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="YES"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/no_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="NO"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
            </RadioGroup>
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:text="Question 2:   Which of the following animals are cats?"
                android:textColor="#E1E1E1"
                android:textSize="32sp" />
            <GridLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginBottom="16dp"
                android:columnCount="2"
                android:rowCount="2">
                <CheckBox
                    android:id="@+id/lion_check_box"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="24dp"
                    android:text="Lion"
                    android:textColor="#E1E1E1"
                    android:textSize="16sp" />
                <CheckBox
                    android:id="@+id/tiger_check_box"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="24dp"
                    android:text="Tiger"
                    android:textColor="#E1E1E1"
                    android:textSize="16sp" />
                <CheckBox
                    android:id="@+id/elephant_check_box"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="24dp"
                    android:text="Elephant"
                    android:textColor="#E1E1E1"
                    android:textSize="16sp" />
                <CheckBox
                    android:id="@+id/whale_check_box"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="24dp"
                    android:text="Whale"
                    android:textColor="#E1E1E1"
                    android:textSize="16sp" />
            </GridLayout>
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:text="Question 3:   What are baby goats called?"
                android:textColor="#E1E1E1"
                android:textSize="32sp" />
            <RadioGroup
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginBottom="16dp"
                android:orientation="vertical">
                <RadioButton
                    android:id="@+id/calves_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Calves"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/chicks_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Chicks"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/kids_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Kids"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/puppies_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Puppies"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
            </RadioGroup>
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:text="Question 4:   Which one of the following animals BARK?"
                android:textColor="#E1E1E1"
                android:textSize="32sp" />
            <RadioGroup
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginBottom="16dp"
                android:orientation="vertical"
                android:textColor="#E1E1E1">
                <RadioButton
                    android:id="@+id/cat_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Cat"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/spider_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Spider"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/goat_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Goat (Messi or Ronaldo)"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/dog_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="Dog"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
            </RadioGroup>
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:text="Question 5:   How many legs does a spider have?"
                android:textColor="#E1E1E1"
                android:textSize="32sp" />
            <RadioGroup
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginBottom="16dp"
                android:orientation="vertical"
                android:textColor="#E1E1E1">
                <RadioButton
                    android:id="@+id/eight_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="8"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/hundred_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="100"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/four_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="4"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
                <RadioButton
                    android:id="@+id/two_radio_button"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:paddingLeft="16dp"
                    android:text="2"
                    android:textAppearance="?android:textAppearanceMedium"
                    android:textColor="#E1E1E1" />
            </RadioGroup>
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp"
                android:paddingLeft="8dp"
                android:text="When you are done answering the questions, please click on SUBMIT"
                android:textColor="#E1E1E1"
                android:textSize="16sp" />
        </LinearLayout>
    </ScrollView>
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="16dp"
        android:onClick="submitAnswers"
        android:text="SUBMIT"
        android:textStyle="bold" />
</RelativeLayout>



this is the Java code

package com.example.android.quizapp;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.CheckBox;
import android.widget.EditText;
import android.widget.RadioButton;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

    public void submitAnswers(View view) {

        int score = 0;  //score is initialized to zero each time the Submit button is clicked

        EditText nameField = (EditText) findViewById(R.id.user_name_edit_text);
        String userName = nameField.getText().toString();

        RadioButton yesRadioButton = (RadioButton) findViewById(R.id.yes_radio_button);
        boolean choseYes = yesRadioButton.isChecked();

        RadioButton noRadioButton = (RadioButton) findViewById(R.id.no_radio_button);
        boolean choseNo = noRadioButton.isChecked();

        if (choseYes) {
            score = score + 1;
        }
        if (choseNo) {
            score = score - 1;
        }

        CheckBox lionCheckbox = (CheckBox) findViewById(R.id.lion_check_box);
        boolean isLion = lionCheckbox.isChecked();

        CheckBox tigerCheckbox = (CheckBox) findViewById(R.id.tiger_check_box);
        boolean isTiger = tigerCheckbox.isChecked();

        CheckBox elephantCheckbox = (CheckBox) findViewById(R.id.elephant_check_box);
        boolean isElephant = elephantCheckbox.isChecked();

        CheckBox whaleCheckbox = (CheckBox) findViewById(R.id.whale_check_box);
        boolean isWhale = whaleCheckbox.isChecked();

        if (isLion & isTiger) {
            score = score + 1;
        }
        if (isElephant) {
            score = score - 1;
        }
        if (isWhale) {
            score = score - 1;
        }

        RadioButton calvesRadioButton = (RadioButton) findViewById(R.id.calves_radio_button);
        boolean choseCalves = calvesRadioButton.isChecked();

        RadioButton chicksRadioButton = (RadioButton) findViewById(R.id.chicks_radio_button);
        boolean choseChicks = chicksRadioButton.isChecked();

        RadioButton kidsRadioButton = (RadioButton) findViewById(R.id.kids_radio_button);
        boolean choseKids = kidsRadioButton.isChecked();

        RadioButton puppiesRadioButton = (RadioButton) findViewById(R.id.puppies_radio_button);
        boolean chosePuppies = puppiesRadioButton.isChecked();

        if (choseCalves) {
            score = score - 1;
        }
        if (choseChicks) {
            score = score - 1;
        }
        if (choseKids) {
            score = score + 1;
        }
        if (chosePuppies) {
            score = score - 1;
        }

        RadioButton catRadioButton = (RadioButton) findViewById(R.id.cat_radio_button);
        boolean choseCat = catRadioButton.isChecked();

        RadioButton spiderRadioButton = (RadioButton) findViewById(R.id.spider_radio_button);
        boolean choseSpider = spiderRadioButton.isChecked();

        RadioButton goatRadioButton = (RadioButton) findViewById(R.id.goat_radio_button);
        boolean choseGoat = goatRadioButton.isChecked();

        RadioButton dogRadioButton = (RadioButton) findViewById(R.id.dog_radio_button);
        boolean choseDog = dogRadioButton.isChecked();

        if (choseCat) {
            score = score - 1;
        }
        if (choseSpider) {
            score = score - 1;
        }
        if (choseGoat) {
            score = score - 1;
        }
        if (choseDog) {
            score = score + 1;
        }

        RadioButton eightRadioButton = (RadioButton) findViewById(R.id.eight_radio_button);
        boolean choseEight = eightRadioButton.isChecked();

        RadioButton hundredRadioButton = (RadioButton) findViewById(R.id.hundred_radio_button);
        boolean choseHundred = hundredRadioButton.isChecked();

        RadioButton fourRadioButton = (RadioButton) findViewById(R.id.four_radio_button);
        boolean choseFour = fourRadioButton.isChecked();

        RadioButton twoRadioButton = (RadioButton) findViewById(R.id.two_radio_button);
        boolean choseTwo = twoRadioButton.isChecked();

        if (choseEight) {
            score = score + 1;
        }
        if (choseHundred) {
            score = score - 1;
        }
        if (choseFour) {
            score = score - 1;
        }
        if (choseTwo) {
            score = score - 1;
        }

        Toast.makeText(MainActivity.this, "Well Done " + userName + "!!!" +
                        "\nYour score is " + score + " out of 5",
                Toast.LENGTH_LONG).show();
    }
}



and my style file

<resources>
    <style
        name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
        <item name="colorPrimary">@color/colorPrimary</item>
        <item name="colorPrimaryDark">@color/colorPrimaryDark</item>
        <item name="colorAccent">#d50000</item>
        <item name="colorButtonNormal">#d50000</item>
        <item name="android:textColorPrimary">#E1E1E1</item>
    </style>
</resources>
