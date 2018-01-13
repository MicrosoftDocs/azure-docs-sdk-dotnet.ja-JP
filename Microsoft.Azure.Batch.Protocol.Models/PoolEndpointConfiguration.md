<Type Name="PoolEndpointConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration">
  <TypeSignature Language="C#" Value="public class PoolEndpointConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEndpointConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEndpointConfiguration" />
  <TypeSignature Language="F#" Value="type PoolEndpointConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a18ae-101">プールのエンドポイント構成。</span><span class="sxs-lookup"><span data-stu-id="a18ae-101">The endpoint configuration for a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEndpointConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a18ae-102">PoolEndpointConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a18ae-102">Initializes a new instance of the PoolEndpointConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEndpointConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt; inboundNATPools);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt; inboundNATPools) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.InboundNATPool})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inboundNATPools As IList(Of InboundNATPool))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration inboundNATPools" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inboundNATPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt;" />
      </Parameters>
      <Docs>
        <param name="inboundNATPools"><span data-ttu-id="a18ae-103">個々 のコンピューティング ノードを外部からの特定のポートに対処するために使用する受信の NAT プールの一覧です。</span><span class="sxs-lookup"><span data-stu-id="a18ae-103">A list of inbound NAT pools that can be used to address specific ports on an individual compute node externally.</span></span></param>
        <summary>
            <span data-ttu-id="a18ae-104">PoolEndpointConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a18ae-104">Initializes a new instance of the PoolEndpointConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNATPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt; InboundNATPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt; InboundNATPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration.InboundNATPools" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNATPools As IList(Of InboundNATPool)" />
      <MemberSignature Language="F#" Value="member this.InboundNATPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration.InboundNATPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inboundNATPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundNATPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a18ae-105">取得または個々 のコンピューティング ノードを外部からの特定のポートに対処するために使用する受信の NAT プールの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a18ae-105">Gets or sets a list of inbound NAT pools that can be used to address specific ports on an individual compute node externally.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a18ae-106">Batch プールあたりの着信 NAT プールの最大数は 5 です。</span><span class="sxs-lookup"><span data-stu-id="a18ae-106">The maximum number of inbound NAT pools per Batch pool is 5.</span></span> <span data-ttu-id="a18ae-107">着信 NAT プールの最大数を超えたかどうか、要求は HTTP ステータス コード 400 で失敗します。</span><span class="sxs-lookup"><span data-stu-id="a18ae-107">If the maximum number of inbound NAT pools is exceeded the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEndpointConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolEndpointConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a18ae-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a18ae-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a18ae-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a18ae-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>