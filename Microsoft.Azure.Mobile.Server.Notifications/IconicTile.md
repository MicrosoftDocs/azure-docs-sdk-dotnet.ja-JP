<Type Name="IconicTile" FullName="Microsoft.Azure.Mobile.Server.Notifications.IconicTile">
  <TypeSignature Language="C#" Value="public class IconicTile : Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IconicTile extends Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />
  <TypeSignature Language="VB.NET" Value="Public Class IconicTile&#xA;Inherits MpnsTileMessage" />
  <TypeSignature Language="F#" Value="type IconicTile = class&#xA;    inherit MpnsTileMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            MPNS を対象とするアイコンのタイルを表します。 使用して、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />で<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />MPNS 通知を作成しを使用して送信する、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />です。
            </summary>
    <remarks>
            MPNS アイコン タイルの詳細については、次を参照してください。 <c>http://msdn.microsoft.com/en-us/library/windowsphone/develop/jj207009</c>です。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IconicTile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackgroundColor">
      <MemberSignature Language="C#" Value="public string BackgroundColor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackgroundColor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.BackgroundColor" />
      <MemberSignature Language="VB.NET" Value="Public Property BackgroundColor As String" />
      <MemberSignature Language="F#" Value="member this.BackgroundColor : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.BackgroundColor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタイルの背景色を設定します。 このプロパティを設定すると、携帯電話に設定されている既定のテーマの色。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IconImage">
      <MemberSignature Language="C#" Value="public Uri IconImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri IconImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.IconImage" />
      <MemberSignature Language="VB.NET" Value="Public Property IconImage As Uri" />
      <MemberSignature Language="F#" Value="member this.IconImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.IconImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または中規模から大規模のタイルのサイズのアイコンの画像を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SmallIconImage">
      <MemberSignature Language="C#" Value="public Uri SmallIconImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SmallIconImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.SmallIconImage" />
      <MemberSignature Language="VB.NET" Value="Public Property SmallIconImage As Uri" />
      <MemberSignature Language="F#" Value="member this.SmallIconImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.SmallIconImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または小さなタイル サイズのアイコンの画像を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideContent1">
      <MemberSignature Language="C#" Value="public string WideContent1 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WideContent1" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent1" />
      <MemberSignature Language="VB.NET" Value="Public Property WideContent1 As String" />
      <MemberSignature Language="F#" Value="member this.WideContent1 : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent1" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワイド タイルのサイズの最初の行に表示されるテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideContent2">
      <MemberSignature Language="C#" Value="public string WideContent2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WideContent2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent2" />
      <MemberSignature Language="VB.NET" Value="Public Property WideContent2 As String" />
      <MemberSignature Language="F#" Value="member this.WideContent2 : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワイド タイルのサイズの 2 番目の行に表示されるテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideContent3">
      <MemberSignature Language="C#" Value="public string WideContent3 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WideContent3" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent3" />
      <MemberSignature Language="VB.NET" Value="Public Property WideContent3 As String" />
      <MemberSignature Language="F#" Value="member this.WideContent3 : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent3" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワイド タイルのサイズの 3 番目の行に表示されるテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>