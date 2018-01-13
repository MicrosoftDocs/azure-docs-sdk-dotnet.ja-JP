<Type Name="StagingSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.StagingSettings">
  <TypeSignature Language="C#" Value="public class StagingSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StagingSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.StagingSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class StagingSettings" />
  <TypeSignature Language="F#" Value="type StagingSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9eb0-101">ステージング設定します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-101">Staging settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StagingSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.StagingSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9eb0-102">StagingSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-102">Initializes a new instance of the StagingSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StagingSettings (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object path = null, object enableCompression = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object path, object enableCompression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.StagingSettings.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional path As Object = null, Optional enableCompression As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.StagingSettings : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.StagingSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.StagingSettings (linkedServiceName, additionalProperties, path, enableCompression)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="path" Type="System.Object" />
        <Parameter Name="enableCompression" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="c9eb0-103">ステージングでは、サービス参照のリンクされています。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-103">Staging linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="c9eb0-104">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="c9eb0-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="path"><span data-ttu-id="c9eb0-105">中間のデータを格納するための記憶域へのパス。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-105">The path to storage for storing the interim data.</span></span> <span data-ttu-id="c9eb0-106">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-106">Type: string (or Expression with resultType string).</span></span></param>
        <param name="enableCompression"><span data-ttu-id="c9eb0-107">中間のステージングを使用してデータをコピーするときに、圧縮を使用するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-107">Specifies whether to use compression when copying data via an interim staging.</span></span> <span data-ttu-id="c9eb0-108">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-108">Default value is false.</span></span> <span data-ttu-id="c9eb0-109">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-109">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="c9eb0-110">StagingSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-110">Initializes a new instance of the StagingSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.StagingSettings.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.StagingSettings.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9eb0-111">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="c9eb0-111">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCompression">
      <MemberSignature Language="C#" Value="public object EnableCompression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableCompression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.StagingSettings.EnableCompression" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableCompression As Object" />
      <MemberSignature Language="F#" Value="member this.EnableCompression : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.StagingSettings.EnableCompression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableCompression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9eb0-112">取得または設定は、中間のステージングを使用してデータをコピーするときに、圧縮を使用するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-112">Gets or sets specifies whether to use compression when copying data via an interim staging.</span></span> <span data-ttu-id="c9eb0-113">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-113">Default value is false.</span></span> <span data-ttu-id="c9eb0-114">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-114">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.StagingSettings.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.StagingSettings.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9eb0-115">取得またはリンクされたサービス参照のステージングを設定します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-115">Gets or sets staging linked service reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public object Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.StagingSettings.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As Object" />
      <MemberSignature Language="F#" Value="member this.Path : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.StagingSettings.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9eb0-116">取得または暫定的なデータを格納するためのストレージへのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-116">Gets or sets the path to storage for storing the interim data.</span></span>
            <span data-ttu-id="c9eb0-117">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-117">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.StagingSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="stagingSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9eb0-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c9eb0-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c9eb0-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>