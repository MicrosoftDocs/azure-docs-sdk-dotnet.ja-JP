<Type Name="WindowsPushMessage" FullName="Microsoft.Azure.Mobile.Server.WindowsPushMessage">
  <TypeSignature Language="C#" Value="public class WindowsPushMessage : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsPushMessage extends System.Object implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsPushMessage&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type WindowsPushMessage = class&#xA;    interface IPushMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Notifications.IPushMessage</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("tile")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="35ee3-101"><see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> Windows プッシュ通知サービスを対象とする通知のペイロードを生成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="35ee3-101">The <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> helps generating a notification payload targeting Windows Push Notification Services.</span></span> <span data-ttu-id="35ee3-102">使用して通知を送信できる、<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="35ee3-102">Notifications can be sent using the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsPushMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.WindowsPushMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35ee3-103"><see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35ee3-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsPushMessage (int version, params Microsoft.Azure.Mobile.Server.TileBinding[] bindings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 version, class Microsoft.Azure.Mobile.Server.TileBinding[] bindings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.WindowsPushMessage.#ctor(System.Int32,Microsoft.Azure.Mobile.Server.TileBinding[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (version As Integer, ParamArray bindings As TileBinding())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.WindowsPushMessage : int * Microsoft.Azure.Mobile.Server.TileBinding[] -&gt; Microsoft.Azure.Mobile.Server.WindowsPushMessage" Usage="new Microsoft.Azure.Mobile.Server.WindowsPushMessage (version, bindings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.Int32" />
        <Parameter Name="bindings" Type="Microsoft.Azure.Mobile.Server.TileBinding[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="35ee3-104">タイルの XML スキーマのバージョンこの特定のペイロード用に開発されて (例。「1」または「2」) です。</span><span class="sxs-lookup"><span data-stu-id="35ee3-104">The version of the tile XML schema this particular payload was developed for (e.g. "1" or "2").</span></span></param>
        <param name="bindings"><span data-ttu-id="35ee3-105">このバインディングの初期セット<see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="35ee3-105">An initial set of bindings for this <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="35ee3-106"><see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35ee3-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.WindowsPushMessage.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Mobile.Server.WindowsPushMessage.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35ee3-107">通知と共に Windows プッシュ通知サービスに送信される HTTP ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="35ee3-107">Any additional HTTP headers sent to the Windows Push Notification Services along with the notification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.WindowsPushMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="windowsPushMessage.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35ee3-108">XML 表現を提供、<see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="35ee3-108">Provides an XML representation of the <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> instance.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visual">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Notifications.VisualTile Visual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.Notifications.VisualTile Visual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.WindowsPushMessage.Visual" />
      <MemberSignature Language="VB.NET" Value="Public Property Visual As VisualTile" />
      <MemberSignature Language="F#" Value="member this.Visual : Microsoft.Azure.Mobile.Server.Notifications.VisualTile with get, set" Usage="Microsoft.Azure.Mobile.Server.WindowsPushMessage.Visual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("visual")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Notifications.VisualTile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35ee3-109">A<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" />要素は、定義されているタイル複数のバインド子要素が含まれます。</span><span class="sxs-lookup"><span data-stu-id="35ee3-109">A <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" /> element which contains multiple binding child elements, each of which defines a tile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="XmlPayload">
      <MemberSignature Language="C#" Value="public string XmlPayload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string XmlPayload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.WindowsPushMessage.XmlPayload" />
      <MemberSignature Language="VB.NET" Value="Public Property XmlPayload As String" />
      <MemberSignature Language="F#" Value="member this.XmlPayload : string with get, set" Usage="Microsoft.Azure.Mobile.Server.WindowsPushMessage.XmlPayload" />
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
            <span data-ttu-id="35ee3-110">追加することで、通知をプログラムで構築する代わりに<see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" />インスタンスを<see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />、変更されず、通知ハブに送信される完全な XML 表現を提供することはできます。</span><span class="sxs-lookup"><span data-stu-id="35ee3-110">As an alternative to building the notification programmatically by adding <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" /> instances to the <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, it is possible to provide a complete XML representation which will be sent to the Notification Hub unaltered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>