<Type Name="OutputFileUploadOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions">
  <TypeSignature Language="C#" Value="public class OutputFileUploadOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileUploadOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileUploadOptions" />
  <TypeSignature Language="F#" Value="type OutputFileUploadOptions = class" />
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
            <span data-ttu-id="c981d-101">詳細については、出力ファイルは、アップロードを実行するには、どのような条件を含む操作をアップロードします。</span><span class="sxs-lookup"><span data-stu-id="c981d-101">Details about an output file upload operation, including under what conditions to perform the upload.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileUploadOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions.#ctor" />
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
            <span data-ttu-id="c981d-102">OutputFileUploadOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c981d-102">Initializes a new instance of the OutputFileUploadOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileUploadOptions (Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition uploadCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition uploadCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions.#ctor(Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (uploadCondition As OutputFileUploadCondition)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions : Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition -&gt; Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions uploadCondition" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="uploadCondition" Type="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition" />
      </Parameters>
      <Docs>
        <param name="uploadCondition"><span data-ttu-id="c981d-103">ファイルまたはファイルのセットに、タスクが出力される条件をアップロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c981d-103">The conditions under which the task output file or set of files should be uploaded.</span></span></param>
        <summary>
            <span data-ttu-id="c981d-104">OutputFileUploadOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c981d-104">Initializes a new instance of the OutputFileUploadOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCondition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition UploadCondition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition UploadCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions.UploadCondition" />
      <MemberSignature Language="VB.NET" Value="Public Property UploadCondition As OutputFileUploadCondition" />
      <MemberSignature Language="F#" Value="member this.UploadCondition : Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions.UploadCondition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uploadCondition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c981d-105">取得または設定の条件をタスクの出力ファイルまたはファイルのセットをアップロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c981d-105">Gets or sets the conditions under which the task output file or set of files should be uploaded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c981d-106">既定値は、taskCompletion です。</span><span class="sxs-lookup"><span data-stu-id="c981d-106">The default is taskCompletion.</span></span> <span data-ttu-id="c981d-107">使用可能な値が含まれます: 'taskSuccess'、'タスク失敗'、'taskCompletion'</span><span class="sxs-lookup"><span data-stu-id="c981d-107">Possible values include: 'taskSuccess', 'taskFailure', 'taskCompletion'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputFileUploadOptions.Validate " />
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
            <span data-ttu-id="c981d-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c981d-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c981d-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c981d-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>