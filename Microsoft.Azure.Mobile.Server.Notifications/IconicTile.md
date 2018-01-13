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
            <span data-ttu-id="8d719-101">MPNS を対象とするアイコンのタイルを表します。</span><span class="sxs-lookup"><span data-stu-id="8d719-101">Represents a Iconic Tile targeting MPNS.</span></span> <span data-ttu-id="8d719-102">使用して、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />で<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />MPNS 通知を作成しを使用して送信する、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />です。</span><span class="sxs-lookup"><span data-stu-id="8d719-102">Use the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> with <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> to create an MPNS notification and send it using the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="8d719-103">MPNS アイコン タイルの詳細については、次を参照してください。 <c>http://msdn.microsoft.com/en-us/library/windowsphone/develop/jj207009</c>です。</span><span class="sxs-lookup"><span data-stu-id="8d719-103">For more information about MPNS Iconic Tiles, see <c>http://msdn.microsoft.com/en-us/library/windowsphone/develop/jj207009</c>.</span></span>
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
            <span data-ttu-id="8d719-104"><see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8d719-104">Initialize a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> class.</span></span>
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
            <span data-ttu-id="8d719-105">取得またはタイルの背景色を設定します。</span><span class="sxs-lookup"><span data-stu-id="8d719-105">Gets or sets the background color of the Tile.</span></span> <span data-ttu-id="8d719-106">このプロパティを設定すると、携帯電話に設定されている既定のテーマの色。</span><span class="sxs-lookup"><span data-stu-id="8d719-106">Setting this property overrides the default theme color that is set on the phone.</span></span>
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
            <span data-ttu-id="8d719-107">取得または中規模から大規模のタイルのサイズのアイコンの画像を設定します。</span><span class="sxs-lookup"><span data-stu-id="8d719-107">Gets or sets the icon image for the medium and large tile sizes.</span></span>
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
            <span data-ttu-id="8d719-108">取得または小さなタイル サイズのアイコンの画像を設定します。</span><span class="sxs-lookup"><span data-stu-id="8d719-108">Gets or sets the icon image for the small tile size.</span></span>
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
            <span data-ttu-id="8d719-109">取得またはワイド タイルのサイズの最初の行に表示されるテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="8d719-109">Gets or sets the text that displays on the first row of the wide tile size.</span></span>
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
            <span data-ttu-id="8d719-110">取得またはワイド タイルのサイズの 2 番目の行に表示されるテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="8d719-110">Gets or sets the text that displays on the second row of the wide tile size.</span></span>
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
            <span data-ttu-id="8d719-111">取得またはワイド タイルのサイズの 3 番目の行に表示されるテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="8d719-111">Gets or sets the text that displays on the third row of the wide tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>