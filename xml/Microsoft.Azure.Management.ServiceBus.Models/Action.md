<Type Name="Action" FullName="Microsoft.Azure.Management.ServiceBus.Models.Action">
  <TypeSignature Language="C#" Value="public class Action" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Action extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.Action" />
  <TypeSignature Language="VB.NET" Value="Public Class Action" />
  <TypeSignature Language="F#" Value="type Action = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="97a90-101">フィルター式が一致するメッセージの変換で許可されているフィルター操作を表します。</span><span class="sxs-lookup"><span data-stu-id="97a90-101">Represents the filter actions which are allowed for the transformation of a message that have been matched by a filter expression.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Action ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Action.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="97a90-102">アクション クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97a90-102">Initializes a new instance of the Action class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Action (string sqlExpression = null, Nullable&lt;int&gt; compatibilityLevel = null, Nullable&lt;bool&gt; requiresPreprocessing = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression, valuetype System.Nullable`1&lt;int32&gt; compatibilityLevel, valuetype System.Nullable`1&lt;bool&gt; requiresPreprocessing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Action.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sqlExpression As String = null, Optional compatibilityLevel As Nullable(Of Integer) = null, Optional requiresPreprocessing As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.Action : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.Action" Usage="new Microsoft.Azure.Management.ServiceBus.Models.Action (sqlExpression, compatibilityLevel, requiresPreprocessing)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requiresPreprocessing" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlExpression"><span data-ttu-id="97a90-103">SQL 式です。</span><span class="sxs-lookup"><span data-stu-id="97a90-103">SQL expression.</span></span> <span data-ttu-id="97a90-104">例: MyProperty 'ABC' を =</span><span class="sxs-lookup"><span data-stu-id="97a90-104">e.g. MyProperty='ABC'</span></span></param>
        <param name="compatibilityLevel"><span data-ttu-id="97a90-105">このプロパティは、将来の使用に備えて予約されています。</span><span class="sxs-lookup"><span data-stu-id="97a90-105">This property is reserved for future use.</span></span> <span data-ttu-id="97a90-106">互換性レベルを示す整数値現在にハードコード 20 です。</span><span class="sxs-lookup"><span data-stu-id="97a90-106">An integer value showing the compatibility level, currently hard-coded to 20.</span></span></param>
        <param name="requiresPreprocessing"><span data-ttu-id="97a90-107">前処理を規則の操作が必要かどうかを示す値です。</span><span class="sxs-lookup"><span data-stu-id="97a90-107">Value that indicates whether the rule action requires preprocessing.</span></span></param>
        <summary>
            <span data-ttu-id="97a90-108">アクション クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97a90-108">Initializes a new instance of the Action class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CompatibilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Action.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property CompatibilityLevel As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Action.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="compatibilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97a90-109">取得または設定がこのプロパティは将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="97a90-109">Gets or sets this property is reserved for future use.</span></span> <span data-ttu-id="97a90-110">互換性レベルを示す整数値現在にハードコード 20 です。</span><span class="sxs-lookup"><span data-stu-id="97a90-110">An integer value showing the compatibility level, currently hard-coded to 20.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresPreprocessing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Action.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresPreprocessing As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Action.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requiresPreprocessing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97a90-111">取得またはプリプロセスを規則の操作が必要かどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="97a90-111">Gets or sets value that indicates whether the rule action requires preprocessing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Action.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Action.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlExpression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97a90-112">取得または SQL 式を設定します。</span><span class="sxs-lookup"><span data-stu-id="97a90-112">Gets or sets SQL expression.</span></span> <span data-ttu-id="97a90-113">例: MyProperty 'ABC' を =</span><span class="sxs-lookup"><span data-stu-id="97a90-113">e.g. MyProperty='ABC'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>