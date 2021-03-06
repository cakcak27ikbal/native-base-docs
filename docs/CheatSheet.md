# NativeBase Cheat Sheet

### Basic Layout
<table width="80%" class="table table-hover">
            <thead>
                <tr>
                    <th>Component</th>
                    <th>Description</th>
                    <th>Replacing Component</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>&lt;Container></td>
                    <td>Complete section of screen</td>
                    <td>React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            View
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>&lt;Header></td>
                    <td>Header or Navbar of screen</td>
                    <td>React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            View
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>&lt;Content></td>
                    <td>Body element of screen</td>
                    <td>React Native
                        <a href="https://github.com/APSL/react-native-keyboard-aware-scroll-view">
                            KeyboardAwareScrollView
                        </a>
                    </td>
                </tr>
            </tbody>
        </table><br />

<h3>Components</h3>

<table width="100%" class="table table-hover">
            <thead>
                <tr>
                    <th>Component</th>
                    <th>Description</th>
                    <th>Replacing Component</th>
                </tr>
            </thead>
            <tbody>

                <!-- Accordion -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Accordion></td>
                    <td>Toggle the visibility of content across items of your screen</td>
                    <td>
                       -
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>dataArray</li>
                        </ul>
                    </td>
                    <td>Array of data chunks to render iteratively</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>expanded</li>
                        </ul>
                    </td>
                    <td>Index of accordion set open</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>headerStyle</li>
                        </ul>
                    </td>
                    <td>Style accordion header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>contentStyle</li>
                        </ul>
                    </td>
                    <td>Style accordion content</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>icon</li>
                        </ul>
                    </td>
                    <td>Icon when accordion is closed</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>expandedIcon</li>
                        </ul>
                    </td>
                    <td>Icon when accordion is open</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iconStyle</li>
                        </ul>
                    </td>
                    <td>Icon style when accordion is closed</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>expandedIconStyle</li>
                        </ul>
                    </td>
                    <td>Icon style when accordion is open</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderHeader</li>
                        </ul>
                    </td>
                    <td>Custom design of Accordion header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderContent</li>
                        </ul>
                    </td>
                    <td>Custom design of Accordion content</td>
                    <td></td>
                </tr>


                <!-- ActionSheet -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;ActionSheet></td>
                    <td>Flexible and extensible content container</td>
                    <td>
                        React Native
                        <a href="http://facebook.github.io/react-native/docs/modal.html">
                            Modal
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>options</li>
                        </ul>
                    </td>
                    <td>List of button titles</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>cancelButtonIndex</li>
                        </ul>
                    </td>
                    <td>index of cancel button in 'options'</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>destructiveButtonIndex</li>
                        </ul>
                    </td>
                    <td>index of destructive button in 'options'</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>title</li>
                        </ul>
                    </td>
                    <td>a title to show above the ActionSheet</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>show()</li>
                        </ul>
                    </td>
                    <td>show ActionSheet</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>hide()</li>
                        </ul>
                    </td>
                    <td>hide ActionSheet</td>
                    <td></td>
                </tr>


                <!-- Badge -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Badge></td>
                    <td>
                        Numerical indicators used to notify an element<br />
                    </td>
                    <td>React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            View
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>primary</li>
                        </ul>
                    </td>
                    <td>blue background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>success</li>
                        </ul>
                    </td>
                    <td>green background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>info</li>
                        </ul>
                    </td>
                    <td>light blue background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>warning</li>
                        </ul>
                    </td>
                    <td>yellow background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>danger</li>
                        </ul>
                    </td>
                    <td>red background color</td>
                    <td></td>
                </tr>


                <!-- Button -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Button></td>
                    <td>Submit or reset a form, Navigate etc</td>
                    <td>
                        React Native - <br />
                        <a href="https://facebook.github.io/react-native/docs/touchableopacity.html">
                            TouchableOpacity
                        </a>(iOS)<br />
                        <a href="http://facebook.github.io/react-native/docs/touchablenativefeedback.html">
                            TouchableNativeFeedback
                        </a>(Android)
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>active</li>
                        </ul>
                    </td>
                    <td>state of button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>transparent</li>
                        </ul>
                    </td>
                    <td>renders child element of button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>bordered</li>
                        </ul>
                    </td>
                    <td>outline button style</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>rounded</li>
                        </ul>
                    </td>
                    <td>button with slightly round shaped edges</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>block</li>
                        </ul>
                    </td>
                    <td>block level button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>full</li>
                        </ul>
                    </td>
                    <td>full width button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disabled</li>
                        </ul>
                    </td>
                    <td>disables click option for button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>small</li>
                        </ul>
                    </td>
                    <td>small size button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>large</li>
                        </ul>
                    </td>
                    <td>large size button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iconLeft</li>
                        </ul>
                    </td>
                    <td>aligns icon to the left in button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iconRight</li>
                        </ul>
                    </td>
                    <td>aligns icon to the right in button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>light</li>
                        </ul>
                    </td>
                    <td>light white background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>primary</li>
                        </ul>
                    </td>
                    <td>blue background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>success</li>
                        </ul>
                    </td>
                    <td>green background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>info</li>
                        </ul>
                    </td>
                    <td>light blue background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>warning</li>
                        </ul>
                    </td>
                    <td>yellow background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>danger</li>
                        </ul>
                    </td>
                    <td>red background color</td>
                    <td></td>
                </tr>




                <!-- Card -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Card></td>
                    <td>Flexible and extensible content container</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            View
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>transparent</li>
                        </ul>
                    </td>
                    <td>
                        iOS - no card shadow<br />
                        Android - no elevation
                    </td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>dataArray</li>
                        </ul>
                    </td>
                    <td>array of data chunks to render iteratively</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderRow</li>
                        </ul>
                    </td>
                    <td>Flag indicating whether empty section headers should be rendered</td>
                    <td></td>
                </tr>


                <!-- CardItem -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;CardItem></td>
                    <td>Child component of &lt;Card></td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/touchableopacity.html">
                            TouchableOpacity 
                        </a> / 
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            View
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>header</li>
                        </ul>
                    </td>
                    <td>renders text as header for cards</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>cardBody</li>
                        </ul>
                    </td>
                    <td>body section for card</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>footer</li>
                        </ul>
                    </td>
                    <td>renders text as footer for cards</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>button</li>
                        </ul>
                    </td>
                    <td>navigate on click of a card item</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>bordered</li>
                        </ul>
                    </td>
                    <td>adds border to card item</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>first</li>
                        </ul>
                    </td>
                    <td>custom card border radius</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>last</li>
                        </ul>
                    </td>
                    <td>custom card border radius</td>
                    <td></td>
                </tr>





                <!-- Check Box-->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;CheckBox></td>
                    <td>Multiple selections from a set of choices</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/touchableopacity.html">
                            TouchableOpacity
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>checked</li>
                        </ul>
                    </td>
                    <td>represents the state value of an item</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>color</li>
                        </ul>
                    </td>
                    <td>background color of checkbox</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onPress</li>
                        </ul>
                    </td>
                    <td>Handler to be called when checkbox is tapped</td>
                    <td></td>
                </tr>



                <!-- Content-->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Content></td>
                    <td>Renders as body element of your screen</td>
                    <td>
                        React Native
                        <a href="https://github.com/APSL/react-native-keyboard-aware-scroll-view">
                            KeyboardAwareScrollView
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>padder</li>
                        </ul>
                    </td>
                    <td>applies margin at all sides to Content section</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disableKBDismissScroll</li>
                        </ul>
                    </td>
                    <td>disables automatic scroll on focus</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>enableResetScrollToCoords</li>
                        </ul>
                    </td>
                    <td>lets the user enable or disable automatic resetScrollToCoords</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>contentContainerStyle</li>
                        </ul>
                    </td>
                    <td>lets the user style the <code>Content</code> component.</td>
                    <td></td>
                </tr>



                <!-- Date Picker -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;DatePicker></td>
                    <td>Select a date from a time range</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/datepickerios">
                            DatePickerIOS
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>defaultDate</li>
                        </ul>
                    </td>
                    <td>Sets default date in calendar</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>minimumDate</li>
                        </ul>
                    </td>
                    <td>Sets minimum date that can be set in calendar</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>maximumDate</li>
                        </ul>
                    </td>
                    <td>Sets maximum date that can be set in calender</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>androidMode</li>
                        </ul>
                    </td>
                    <td>can take either of values 'default','calendar','spinner'</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>animationType</li>
                        </ul>
                    </td>
                    <td>can take either of values 'fade','slide','none'</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disabled</li>
                        </ul>
                    </td>
                    <td>Prevent user from making selection of date</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iconStyle</li>
                        </ul>
                    </td>
                    <td>Icon style when accordion is closed</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>expandedIconStyle</li>
                        </ul>
                    </td>
                    <td>Icon style when accordion is open</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderHeader</li>
                        </ul>
                    </td>
                    <td>Custom design of Accordion header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderContent</li>
                        </ul>
                    </td>
                    <td>Custom design of Accordion content</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>supportedOrientations</li>
                        </ul>
                    </td>
                    <td>allows the modal to be rotated to any of the specified orientations</td>
                    <td></td>
                </tr>




                <!-- Deck Swiper -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;DeckSwiper></td>
                    <td>Swipes the card to left and right</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>dataSource</li>
                        </ul>
                    </td>
                    <td>Chunk of data(object)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderEmpty</li>
                        </ul>
                    </td>
                    <td>Callback called when all cards are swiped & dataSource empty</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderItem</li>
                        </ul>
                    </td>
                    <td>Callback takes a chunk of data & returns a component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderTop</li>
                        </ul>
                    </td>
                    <td>Callback takes a chunk of data & returns a top layer component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderBottom</li>
                        </ul>
                    </td>
                    <td>Callback takes a chunk of data & returns a bottom layer component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>looping</li>
                        </ul>
                    </td>
                    <td>Loop through the data</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onSwipeRight</li>
                        </ul>
                    </td>
                    <td>Callback called when Card is swiped Right</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onSwipeLeft</li>
                        </ul>
                    </td>
                    <td>Callback called when Card is swiped Left</td>
                    <td></td>
                </tr>



                <!-- FABs -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Fab></td>
                    <td>Provides special type of promoted action.</td>
                    <td>
                        React Native
                        <a href="http://facebook.github.io/react-native/docs/animated.html">
                            &lt;Animated>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>active</li>
                        </ul>
                    </td>
                    <td>toggle status of FAB</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>direction</li>
                        </ul>
                    </td>
                    <td>direction of buttons that popup on click of FAB</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>position</li>
                        </ul>
                    </td>
                    <td>position of FAB on screen</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>containerStyle</li>
                        </ul>
                    </td>
                    <td>padding options to render FAB</td>
                    <td></td>
                </tr>



                <!-- Footer Tabs -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;FooterTab></td>
                    <td>Tabs at Footer which is horizontal region of buttons or links for navigation.</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>active</li>
                        </ul>
                    </td>
                    <td><code>button</code> prop, sets a footer button active</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>badge</li>
                        </ul>
                    </td>
                    <td><code>button</code> prop, set to <code>true</code> if using Badges.</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>vertical</li>
                        </ul>
                    </td>
                    <td><code>button</code> prop, vertically align footer elements.
                    <td></td>
                </tr>



                <!-- Form -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Form></td>
                    <td>Includes group of related input components</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>&lt;Input></li>
                        </ul>
                    </td>
                    <td>component for inputting text</td>
                    <td>
                        React Native
                        <a href="http://facebook.github.io/react-native/docs/textinput.html">
                            &lt;TextInput>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>&lt;Item></li>
                        </ul>
                    </td>
                    <td>wrap around component with specific styles</td>
                    <td>
                        React Native
                        <a href="http://facebook.github.io/react-native/docs/touchableopacity.html">
                            &lt;TouchableOpacity>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>&lt;Label></li>
                        </ul>
                    </td>
                    <td>component for displaying text</td>
                    <td>
                        React Native
                        <a href="http://facebook.github.io/react-native/docs/text.html">
                            &lt;Text>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>fixedLabel</li>
                        </ul>
                    </td>
                    <td>label is fixed to the left of the Input</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>floatingLabel</li>
                        </ul>
                    </td>
                    <td>label that animates upwards/downwards when input is selected/erased</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>inlineLabel</li>
                        </ul>
                    </td>
                    <td>label placed to the left of the input element</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>stackedLabel</li>
                        </ul>
                    </td>
                    <td>places the label on top of input element which appears like a stack</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>bordered</li>
                        </ul>
                    </td>
                    <td>includes border with the textbox</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>rounded</li>
                        </ul>
                    </td>
                    <td>includes rounded border with the textbox</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>regular</li>
                        </ul>
                    </td>
                    <td>includes rectangular border with the textbox</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>underline</li>
                        </ul>
                    </td>
                    <td>includes underline border with the textbox</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disabled</li>
                        </ul>
                    </td>
                    <td>disables inputting data</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>placeholderLabel</li>
                        </ul>
                    </td>
                    <td>renders the same way the TextInput does with the form styling of NativeBase</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>placeholder</li>
                        </ul>
                    </td>
                    <td>string that will be rendered before text input has been entered</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>placeholderTextColor</li>
                        </ul>
                    </td>
                    <td>color of the Input placeholder</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>last</li>
                        </ul>
                    </td>
                    <td>style the Form Item for the last Item of the Form</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>error</li>
                        </ul>
                    </td>
                    <td>border color of textbox for invalid input</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>success</li>
                        </ul>
                    </td>
                    <td>border color of textbox for valid input</td>
                    <td></td>
                </tr>



                <!-- Header -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Header></td>
                    <td>Renders as Header for your screen</td>
                    <td>
                        React Native 
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>&lt;Left></li>
                        </ul>
                    </td>
                    <td>components render to the left in Header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>&lt;Body></li>
                        </ul>
                    </td>
                    <td>components render at the centre in Header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>&lt;Right></li>
                        </ul>
                    </td>
                    <td>components render to the right in Header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iosBarStyle</li>
                        </ul>
                    </td>
                    <td>set iOS barStyle</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>androidStatusBarColor</li>
                        </ul>
                    </td>
                    <td>set background color for status bar in android</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>backgroundColor</li>
                        </ul>
                    </td>
                    <td>set background color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>noShadow</li>
                        </ul>
                    </td>
                    <td>removes elevation from android</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>searchBar</li>
                        </ul>
                    </td>
                    <td>add searchBar to header or not</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>rounded</li>
                        </ul>
                    </td>
                    <td>make Header searchBar rounded</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>hasSubtitle</li>
                        </ul>
                    </td>
                    <td>add subtitle to the Header component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>hasSegment</li>
                        </ul>
                    </td>
                    <td>add Segments to Header component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>hasTabs</li>
                        </ul>
                    </td>
                    <td>add Tabs to Header component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>hasText</li>
                        </ul>
                    </td>
                    <td><code>button</code> prop, add padding to Left for Text Button (iOS)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>noLeft</li>
                        </ul>
                    </td>
                    <td>eliminates Left, moves Title to left (Android)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>span</li>
                        </ul>
                    </td>
                    <td>doubles the header sizet</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>transparent</li>
                        </ul>
                    </td>
                    <td>No Border, shadow, elevation</td>
                    <td></td>
                </tr>



                <!-- Icon -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Icon></td>
                    <td>High definition icons and pixel ideal fonts</td>
                    <td>
                        React Native Vector Icons
                        <a href="https://github.com/oblador/react-native-vector-icons#icon-component">
                            &lt;Icon>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>name</li>
                        </ul>
                    </td>
                    <td>name of icon</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>ios</li>
                        </ul>
                    </td>
                    <td>name of the icon for iOS devices</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>android</li>
                        </ul>
                    </td>
                    <td>name of the icon for Android devices</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>active</li>
                        </ul>
                    </td>
                    <td>renders filled icon</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>color</li>
                        </ul>
                    </td>
                    <td>color for icon</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>fontSize</li>
                        </ul>
                    </td>
                    <td>size of icon</td>
                    <td></td>
                </tr>
                 <tr>
                    <td>
                        <ul>
                            <li>type</li>
                        </ul>
                    </td>
                    <td>Specify icon family</td>
                    <td></td>
                </tr>




                <!-- InputGroup -->
                <!-- <tr style="background-color: #f5f5f5">
                    <td>&lt;InputGroup></td>
                    <td>Combines group of components for a textbox</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>borderType</li>
                        </ul>
                    </td>
                    <td>wraps the textbox with predefined border options.</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iconRight</li>
                        </ul>
                    </td>
                    <td>icon in the input text box appears to the right.</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>success</li>
                        </ul>
                    </td>
                    <td>border color of textbox for valid input.</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>error</li>
                        </ul>
                    </td>
                    <td>border color of textbox for invalid input.</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disabled</li>
                        </ul>
                    </td>
                    <td>disables inputting data.</td>
                    <td></td>
                </tr> -->



                <!-- Input -->
                <!-- <tr style="background-color: #f5f5f5">
                    <td>&lt;Input></td>
                    <td>Component for inputting text </td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/textinput.html">
                            &lt;TextInput>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>placeholder</li>
                        </ul>
                    </td>
                    <td>string that will be rendered before text input has been entered.</td>
                    <td></td>
                </tr> -->



                <!-- Layout -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Grid></td>
                    <td>Cellular structure composed of Rows and Cols</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Col></td>
                    <td>Column component for grid</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Row></td>
                    <td>Row component for grid</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>



                <!-- List -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;List></td>
                    <td>Specifying lists of information</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>dataArray</li>
                        </ul>
                    </td>
                    <td>array of data chunks to render iteratively.</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderRow</li>
                        </ul>
                    </td>
                    <td>
                        Callback which takes a chunk of data from dataArray and returns as a component.
                    </td>
                    <td></td>
                </tr>


                <!-- ListItem -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;ListItem></td>
                    <td>Child component of &lt;List></td>
                    <td>
                        React Native<br />
                        <a href="http://facebook.github.io/react-native/docs/touchableopacity.html">
                            &lt;TouchableOpacity>
                        </a> - iOS<br />
                        <a href="http://facebook.github.io/react-native/docs/touchablenativefeedback.html">
                            &lt;TouchableNativeFeedback>
                        </a> - Android
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>button</li>
                        </ul>
                    </td>
                    <td>navigate on click of a list item</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>selected</li>
                        </ul>
                    </td>
                    <td>highlights the selected item</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>enableEmptySections</li>
                        </ul>
                    </td>
                    <td>flag indicating whether empty section headers should be rendered</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>itemDivider</li>
                        </ul>
                    </td>
                    <td>organize and group the list items</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>itemHeader</li>
                        </ul>
                    </td>
                    <td>style the item as the header for the ListItes</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>first</li>
                        </ul>
                    </td>
                    <td>adds style of first ListItem</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>last</li>
                        </ul>
                    </td>
                    <td>adds style of last ListItem</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>icon</li>
                        </ul>
                    </td>
                    <td>to have list styling of icons</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>avatar</li>
                        </ul>
                    </td>
                    <td>style the list to have Avatars</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>thumbnail</li>
                        </ul>
                    </td>
                    <td>style the list to have Thumbnails</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>noIndent</li>
                        </ul>
                    </td>
                    <td>removes margin from left</td>
                    <td></td>
                </tr>




                <!--Picker-->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Picker></td>
                    <td>Native picker component</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/picker.html">
                            &lt;Picker>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderHeader</li>
                        </ul>
                    </td>
                    <td>makes component that appears as header of the Picker</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>headerStyle</li>
                        </ul>
                    </td>
                    <td>custom style to be given to Header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>headerBackButtonText</li>
                        </ul>
                    </td>
                    <td>custom text for the header back button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>headerBackButtonTextStyle</li>
                        </ul>
                    </td>
                    <td>custom text style for the header back button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>headerTitleStyle</li>
                        </ul>
                    </td>
                    <td>custom title style for the header title</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iosIcon</li>
                        </ul>
                    </td>
                    <td>icon with picker dropdown</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>iosHeader</li>
                        </ul>
                    </td>
                    <td>custom text for the header title</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>textStyle</li>
                        </ul>
                    </td>
                    <td>text style of header</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>itemStyle</li>
                        </ul>
                    </td>
                    <td>style of items in the Picker</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>itemTextStyle</li>
                        </ul>
                    </td>
                    <td>text style of item component in Picker</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>supportedOrientations</li>
                        </ul>
                    </td>
                    <td>allows the modal to be rotated to any of the specified orientations</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>placeholder</li>
                        </ul>
                    </td>
                    <td>default placeholder when no value is selected in iOS</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>placeholderStyle</li>
                        </ul>
                    </td>
                    <td>Custom style for placeholder text in iOS</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>placeholderIconColor</li>
                        </ul>
                    </td>
                    <td>Set placeholder icon color in iOS</td>
                    <td></td>
                </tr>




                <!--Radio Button-->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Radio></td>
                    <td>Single selection from a set of choices</td>
                    <td>
                        React Native
                        <a href="http://facebook.github.io/react-native/docs/touchableopacity.html">
                            &lt;TouchableOpacity>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>selected</li>
                        </ul>
                    </td>
                    <td>represents the state value of an item</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>color</li>
                        </ul>
                    </td>
                    <td>inactive radio color</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>selectedColor</li>
                        </ul>
                    </td>
                    <td>active radio color</td>
                    <td></td>
                </tr>




                <!--Search bar-->
                <tr style="background-color: #f5f5f5">
                    <td>Searchbar</td>
                    <td>Includes search bar in the &lt;Header> section</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>rounded</li>
                        </ul>
                    </td>
                    <td>wraps the search bar with predefined border options</td>
                    <td></td>
                </tr>



                <!-- Segment -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Segment></td>
                    <td>Best used as an alternative for tabs</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>




                <!-- Spinner -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Spinner></td>
                    <td>Page loader</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/activityindicator.html">
                            &lt;ActivityIndicator>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>color</li>
                        </ul>
                    </td>
                    <td>color of Spinner.</td>
                    <td></td>
                </tr>




                <!-- Swipeable List(Multiple Rows) -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Swipeable List><br/>(Multiple Rows)</td>
                    <td>Swipeable List are ListItems that swipe open and close</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>dataSource</li>
                        </ul>
                    </td>
                    <td>data chunks to render iteratively</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderRow</li>
                        </ul>
                    </td>
                    <td>Callback which takes a chunk of data from dataSource and returns as a body component, which is visible</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderLeftHiddenRow</li>
                        </ul>
                    </td>
                    <td>Callback which takes a chunk of data from dataSource and returns as a left component, which is hidden</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>renderRightHiddenRow</li>
                        </ul>
                    </td>
                    <td>Callback which takes a chunk of data from dataSource and returns as a right component, which is hidden</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>leftOpenValue</li>
                        </ul>
                    </td>
                    <td>TranslateX value for opening the row to the left (Positive Value)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>rightOpenValue</li>
                        </ul>
                    </td>
                    <td>TranslateX value for opening the row to the right (Negative Value)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>closeOnRowBeginSwipe</li>
                        </ul>
                    </td>
                    <td>Open row be closed as soon as a row begin to swipe open</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>swipeToOpenPercent</li>
                        </ul>
                    </td>
                    <td>Swipe percent of left/right component's width to trigger the row opening</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disableLeftSwipe</li>
                        </ul>
                    </td>
                    <td>Disable ability to swipe the row left</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disableRightSwipe</li>
                        </ul>
                    </td>
                    <td>Disable ability to swipe the row right</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onRowOpen, onRowClose</li>
                        </ul>
                    </td>
                    <td>Callback function which triggers when a swipe row is animating open/close</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onRowDidOpen, onRowDidClose</li>
                        </ul>
                    </td>
                    <td>Callback function which triggers when a swipe row has animated open/close</td>
                    <td></td>
                </tr>

                



                <!-- Swipeable List(Single Row) -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Swipeable List><br/>(Single Row)</td>
                    <td>Single Swipable ListItem (Outside List)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>body</li>
                        </ul>
                    </td>
                    <td>Native Base or React Native component(Visible Component)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>left</li>
                        </ul>
                    </td>
                    <td>Native Base or React Native component(Left hidden Component)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>right</li>
                        </ul>
                    </td>
                    <td>Native Base or React Native component(Right hidden Component)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>leftOpenValue</li>
                        </ul>
                    </td>
                    <td>TranslateX value for opening the row to the left (Positive Value)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>rightOpenValue</li>
                        </ul>
                    </td>
                    <td>TranslateX value for opening the row to the right (Negative Value)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>stopLeftSwipe</li>
                        </ul>
                    </td>
                    <td>TranslateX value to stop the row to the swipe left (Positive number)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>stopRightSwipe</li>
                        </ul>
                    </td>
                    <td>TranslateX value to stop the row to the swipe right (Negative number)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>swipeToOpenPercent</li>
                        </ul>
                    </td>
                    <td>Swipe percent of left/right component's width to trigger the row opening</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disableLeftSwipe</li>
                        </ul>
                    </td>
                    <td>Disable ability to swipe the row left</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>disableRightSwipe</li>
                        </ul>
                    </td>
                    <td>Disable ability to swipe the row right</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onRowOpen, onRowClose</li>
                        </ul>
                    </td>
                    <td>Callback function which triggers when a swipe row is animating open/close</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>openLeftRow, openRightRow</li>
                        </ul>
                    </td>
                    <td>Dynamically toggle SwipeRow</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>style</li>
                        </ul>
                    </td>
                    <td>Style body</td>
                    <td></td>
                </tr>

                


                <!-- Tabs -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Tabs></td>
                    <td>Horizontal page swiper</td>
                    <td>
                        react-native-scrollable-tab-view
                        <a href="https://github.com/brentvatne/react-native-scrollable-tab-view">
                            &lt;ScrollableTabView>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>locked</li>
                        </ul>
                    </td>
                    <td>disable swipe</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>initialPage</li>
                        </ul>
                    </td>
                    <td>set default active tab</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>page</li>
                        </ul>
                    </td>
                    <td>set selected tab</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>tabBarPosition</li>
                        </ul>
                    </td>
                    <td>set position of Tabs</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>tabBarUnderlineStyle</li>
                        </ul>
                    </td>
                    <td>style of the default tab bar's underline</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onChangeTab</li>
                        </ul>
                    </td>
                    <td>function to call when tab changes</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onScroll</li>
                        </ul>
                    </td>
                    <td>function to call when pages are sliding</td>
                    <td></td>
                </tr>




                <!-- Tab, TabHeading -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Tab>,&lt;TabHeading></td>
                    <td>Individual Tab</td>
                    <td>
                        react-native-scrollable-tab-view
                        <a href="https://github.com/brentvatne/react-native-scrollable-tab-view">
                            &lt;ScrollableTabView>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>heading(only for Tab)</li>
                        </ul>
                    </td>
                    <td>Label String, or Component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>style(only for TabHeading)</li>
                        </ul>
                    </td>
                    <td>Style for TabHeading Component</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>tabStyle</li>
                        </ul>
                    </td>
                    <td>Style for tab bar</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>activeTabStyle</li>
                        </ul>
                    </td>
                    <td>Style for active tab bar</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>textStyle</li>
                        </ul>
                    </td>
                    <td>Style for text</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>activeTextStyle</li>
                        </ul>
                    </td>
                    <td>Style for active text</td>
                    <td></td>
                </tr>




                <!-- ScrollableTab -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;ScrollableTab></td>
                    <td>Horizontal scrolling of tabs</td>
                    <td>
                        react-native-scrollable-tab-view
                        <a href="https://github.com/brentvatne/react-native-scrollable-tab-view">
                            &lt;ScrollableTabView>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>style</li>
                        </ul>
                    </td>
                    <td>Style for ScrollableTab</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>tabsContainerStyle</li>
                        </ul>
                    </td>
                    <td>Style for tabs within ScrollableTab</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>underlineStyle</li>
                        </ul>
                    </td>
                    <td>Style of the Scrollable Tab's underline</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onScroll</li>
                        </ul>
                    </td>
                    <td>Function to call when pages are sliding</td>
                    <td></td>
                </tr>




                <!-- Thumbnail -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Thumbnail></td>
                    <td>Showcase an image with variuos dimensions and shapes</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/image.html">
                            &lt;Image>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>source</li>
                        </ul>
                    </td>
                    <td>size of icon</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>circle</li>
                        </ul>
                    </td>
                    <td>shape of thumbnail (default)</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>square</li>
                        </ul>
                    </td>
                    <td>shape of thumbnail</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>small</li>
                        </ul>
                    </td>
                    <td>small thumbnail with width and height of 36px</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>large</li>
                        </ul>
                    </td>
                    <td>large thumbnail with width and height of 80px</td>
                    <td></td>
                </tr>



                <!-- Toast -->
                <tr style="background-color: #f5f5f5">
                    <td>&lt;Toast></td>
                    <td>Display quick warning or error messages</td>
                    <td>
                        React Native
                        <a href="https://facebook.github.io/react-native/docs/view.html">
                            &lt;View>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>text</li>
                        </ul>
                    </td>
                    <td>text content to be shown in the toast</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>textStyle</li>
                        </ul>
                    </td>
                    <td>style text content for toast</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>buttonText</li>
                        </ul>
                    </td>
                    <td>text to be displayed inside the button</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>buttonTextStyle</li>
                        </ul>
                    </td>
                    <td>style button text for toast</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>buttonStyle</li>
                        </ul>
                    </td>
                    <td>style button for toast</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>position</li>
                        </ul>
                    </td>
                    <td>sets position for the Toast</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>type</li>
                        </ul>
                    </td>
                    <td>sets context to the Toast</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>duration</li>
                        </ul>
                    </td>
                    <td>milliseconds after which Toast disappers</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>onClose</li>
                        </ul>
                    </td>
                    <td>called just before the toast hides</td>
                    <td></td>
                </tr>



                <!-- Typography -->
                <tr style="background-color: #f5f5f5">
                    <td>Typography</td>
                    <td>Heading Tags</td>
                    <td>
                        React Native
                        <a href="http://facebook.github.io/react-native/docs/text.html">
                            &lt;Text>
                        </a>
                    </td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>H1</li>
                        </ul>
                    </td>
                    <td>font-size: 27</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>H2</li>
                        </ul>
                    </td>
                    <td>font-size: 24</td>
                    <td></td>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>H3</li>
                        </ul>
                    </td>
                    <td>font-size: 21</td>
                    <td></td>
                </tr>
            </tbody>
        </table>
