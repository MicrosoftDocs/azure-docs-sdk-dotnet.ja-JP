<Type Name="ContainerConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration">
  <TypeSignature Language="C#" Value="public class ContainerConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ContainerConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerConfiguration" />
  <TypeSignature Language="F#" Value="type ContainerConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="09b2a-101">コンテナーが有効なプールの構成。</span><span class="sxs-lookup"><span data-stu-id="09b2a-101">The configuration for container-enabled pools.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09b2a-102">ContainerConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="09b2a-102">Initializes a new instance of the ContainerConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerConfiguration (System.Collections.Generic.IList&lt;string&gt; containerImageNames = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; containerRegistries = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; containerImageNames, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; containerRegistries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional containerImageNames As IList(Of String) = null, Optional containerRegistries As IList(Of ContainerRegistry) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration (containerImageNames, containerRegistries)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerImageNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="containerRegistries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt;" />
      </Parameters>
      <Docs>
        <param name="containerImageNames"><span data-ttu-id="09b2a-103">コンテナー イメージ名のコレクション。</span><span class="sxs-lookup"><span data-stu-id="09b2a-103">The collection of container image names.</span></span></param>
        <param name="containerRegistries"><span data-ttu-id="09b2a-104">追加のプライベート レジストリのコンテナーをプルできます。</span><span class="sxs-lookup"><span data-stu-id="09b2a-104">Additional private registries from which containers can be pulled.</span></span></param>
        <summary>
            <span data-ttu-id="09b2a-105">ContainerConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="09b2a-105">Initializes a new instance of the ContainerConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerImageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContainerImageNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContainerImageNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerImageNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerImageNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContainerImageNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerImageNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerImageNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09b2a-106">取得またはコンテナーのイメージ名のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="09b2a-106">Gets or sets the collection of container image names.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="09b2a-107">これが"docker pull"に指定された完全なイメージの参照です。</span><span class="sxs-lookup"><span data-stu-id="09b2a-107">This is the full image reference, as would be specified to "docker pull".</span></span> <span data-ttu-id="09b2a-108">イメージが代替のレジストリで完全修飾されていない限り、既定の Docker レジストリからイメージが供給されます。</span><span class="sxs-lookup"><span data-stu-id="09b2a-108">An image will be sourced from the default Docker registry unless the image is fully qualified with an alternative registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; ContainerRegistries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; ContainerRegistries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerRegistries" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistries As IList(Of ContainerRegistry)" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistries : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.ContainerRegistries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerRegistries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09b2a-109">取得またはコンテナーをプルする追加のプライベート レジストリを設定します。</span><span class="sxs-lookup"><span data-stu-id="09b2a-109">Gets or sets additional private registries from which containers can be pulled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="09b2a-110">資格情報を必要とするプライベート レジストリからイメージをダウンロードする必要がある場合は、そのそれらの資格情報をここで提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="09b2a-110">If any images must be downloaded from a private registry which requires credentials, then those credentials must be provided here.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public static string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.Type" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerConfiguration.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>