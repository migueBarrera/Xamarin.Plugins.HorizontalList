Xamari.Forms.Plugin.HorizontalList!
===================


HorizontalList for Xamarin.Forms. Work with .net Standard.

Install on .Net Standard Library.

## NuGet
* Available on NuGet: [Xamarin.Plugin.HorizontalList](https://www.nuget.org/packages/Xamarin.Forms.Plugin.HorizontalList/)


----------


Properties
-------------


> - ItemsSource : Soruce of List.
> - ItemTemplate : Template for item.  It's needed to work.
> - ListOrientation = Default is Vertical.

How use it
-------------

##xaml ##

> Import : `xmlns:control="clr-namespace:HorizontalList;assembly=HorizontalList"`

> Use it : 

    <ContentPage.Content>
        <control:HorizontalList
            ItemsSource="{Binding MyList}"
            ListOrientation="Horizontal" >
            <control:HorizontalList.ItemTemplate >
                <DataTemplate>
                    <Grid>
                        <Label Text="{Binding Name}" />
                    </Grid>
                </DataTemplate>
            </control:HorizontalList.ItemTemplate>
        </control:HorizontalList>
    </ContentPage.Content>
