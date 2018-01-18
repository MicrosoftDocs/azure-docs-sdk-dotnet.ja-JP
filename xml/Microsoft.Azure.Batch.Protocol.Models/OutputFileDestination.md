<Type Name="OutputFileDestination" FullName="Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination">
  <TypeSignature Language="C#" Value="public class OutputFileDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileDestination" />
  <TypeSignature Language="F#" Value="type OutputFileDestination = class" />
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
            <span data-ttu-id="bfcf8-101">転送先ファイルをアップロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="bfcf8-101">The destination to which a file should be uploaded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileDestination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination.#ctor" />
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
            <span data-ttu-id="bfcf8-102">OutputFileDestination クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bfcf8-102">Initializes a new instance of the OutputFileDestination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileDestination (Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination container = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination container) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination.#ctor(Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional container As OutputFileBlobContainerDestination = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination : Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination -&gt; Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination" Usage="new Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination container" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="container" Type="Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination" />
      </Parameters>
      <Docs>
        <param name="container"><span data-ttu-id="bfcf8-103">ファイルのアップロード先 Azure blob ストレージ内の位置。</span><span class="sxs-lookup"><span data-stu-id="bfcf8-103">A location in Azure blob storage to which files are uploaded.</span></span></param>
        <summary>
            <span data-ttu-id="bfcf8-104">OutputFileDestination クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bfcf8-104">Initializes a new instance of the OutputFileDestination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As OutputFileBlobContainerDestination" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfcf8-105">取得またはファイルのアップロード先 Azure blob ストレージの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="bfcf8-105">Gets or sets a location in Azure blob storage to which files are uploaded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputFileDestination.Validate " />
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
            <span data-ttu-id="bfcf8-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="bfcf8-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bfcf8-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bfcf8-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>