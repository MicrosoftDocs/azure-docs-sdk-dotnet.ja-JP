<Type Name="SnapshotRecoveryRequest" FullName="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest">
  <TypeSignature Language="C#" Value="public class SnapshotRecoveryRequest : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SnapshotRecoveryRequest extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class SnapshotRecoveryRequest&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SnapshotRecoveryRequest = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d6716-101">アプリの回復操作に関する詳細情報。</span><span class="sxs-lookup"><span data-stu-id="d6716-101">Details about app recovery operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnapshotRecoveryRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d6716-102">SnapshotRecoveryRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d6716-102">Initializes a new instance of the SnapshotRecoveryRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnapshotRecoveryRequest (string id = null, string name = null, string kind = null, string type = null, string snapshotTime = null, Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget recoveryTarget = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;bool&gt; recoverConfiguration = null, Nullable&lt;bool&gt; ignoreConflictingHostNames = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string snapshotTime, class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget recoveryTarget, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;bool&gt; recoverConfiguration, valuetype System.Nullable`1&lt;bool&gt; ignoreConflictingHostNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.#ctor(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional snapshotTime As String = null, Optional recoveryTarget As SnapshotRecoveryTarget = null, Optional overwrite As Nullable(Of Boolean) = null, Optional recoverConfiguration As Nullable(Of Boolean) = null, Optional ignoreConflictingHostNames As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest : string * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest (id, name, kind, type, snapshotTime, recoveryTarget, overwrite, recoverConfiguration, ignoreConflictingHostNames)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.String" />
        <Parameter Name="recoveryTarget" Type="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="recoverConfiguration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ignoreConflictingHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="d6716-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="d6716-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="d6716-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="d6716-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="d6716-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="d6716-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="d6716-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="d6716-106">Resource type.</span></span></param>
        <param name="snapshotTime"><span data-ttu-id="d6716-107">特定の時点 をアプリの回復を実行し、DateTime 文字列として書式設定します。</span><span class="sxs-lookup"><span data-stu-id="d6716-107">Point in time in which the app recovery should be attempted, formatted as a DateTime string.</span></span></param>
        <param name="recoveryTarget"><span data-ttu-id="d6716-108">Web アプリに書き込まれるスナップショットの内容を指定します。</span><span class="sxs-lookup"><span data-stu-id="d6716-108">Specifies the web app that snapshot contents will be written to.</span></span></param>
        <param name="overwrite"><span data-ttu-id="d6716-109">場合&lt;コード&gt;true&lt;/code&gt;ソース アプリを上書きできるは、回復操作、それ以外の&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="d6716-109">If &lt;code&gt;true&lt;/code&gt; the recovery operation can overwrite source app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="recoverConfiguration"><span data-ttu-id="d6716-110">True の場合、コンテンツ、だけでなく、サイトの構成に戻ります。</span><span class="sxs-lookup"><span data-stu-id="d6716-110">If true, site configuration, in addition to content, will be reverted.</span></span></param>
        <param name="ignoreConflictingHostNames"><span data-ttu-id="d6716-111">True の場合、ターゲット web アプリに回復するときにカスタム ホスト名の競合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="d6716-111">If true, custom hostname conflicts will be ignored when recovering to a target web app.</span></span>
            <span data-ttu-id="d6716-112">この設定を必要なは、RecoverConfiguration が有効になっている場合だけです。</span><span class="sxs-lookup"><span data-stu-id="d6716-112">This setting is only necessary when RecoverConfiguration is enabled.</span></span></param>
        <summary>
            <span data-ttu-id="d6716-113">SnapshotRecoveryRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d6716-113">Initializes a new instance of the SnapshotRecoveryRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreConflictingHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreConflictingHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreConflictingHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.IgnoreConflictingHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreConflictingHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreConflictingHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.IgnoreConflictingHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreConflictingHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6716-114">取得または設定の場合は、ターゲットの web アプリに回復する場合は true、カスタム ホスト名の競合は無視されます。</span><span class="sxs-lookup"><span data-stu-id="d6716-114">Gets or sets if true, custom hostname conflicts will be ignored when recovering to a target web app.</span></span>
            <span data-ttu-id="d6716-115">この設定を必要なは、RecoverConfiguration が有効になっている場合だけです。</span><span class="sxs-lookup"><span data-stu-id="d6716-115">This setting is only necessary when RecoverConfiguration is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6716-116">場合取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; 回復操作は、アプリのソースを上書きできます。 それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code。&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="d6716-116">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; the recovery operation can overwrite source app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverConfiguration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RecoverConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RecoverConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoverConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoverConfiguration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RecoverConfiguration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoverConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoverConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6716-117">取得または設定のコンテンツだけでなく、true の場合、サイトの構成を元に戻す場合。</span><span class="sxs-lookup"><span data-stu-id="d6716-117">Gets or sets if true, site configuration, in addition to content, will be reverted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryTarget">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget RecoveryTarget { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget RecoveryTarget" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoveryTarget" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryTarget As SnapshotRecoveryTarget" />
      <MemberSignature Language="F#" Value="member this.RecoveryTarget : Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.RecoveryTarget" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryTarget")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryTarget</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6716-118">取得または設定は、スナップショットの内容を書き込む web アプリを指定します。</span><span class="sxs-lookup"><span data-stu-id="d6716-118">Gets or sets specifies the web app that snapshot contents will be written to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotTime">
      <MemberSignature Language="C#" Value="public string SnapshotTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.SnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotTime As String" />
      <MemberSignature Language="F#" Value="member this.SnapshotTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest.SnapshotTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.snapshotTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6716-119">取得または時刻をアプリの回復を実行し、DateTime 文字列として書式設定でポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="d6716-119">Gets or sets point in time in which the app recovery should be attempted, formatted as a DateTime string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>