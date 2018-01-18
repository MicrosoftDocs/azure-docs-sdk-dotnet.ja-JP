<Type Name="InputDirectory" FullName="Microsoft.Azure.Management.BatchAI.Models.InputDirectory">
  <TypeSignature Language="C#" Value="public class InputDirectory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InputDirectory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.InputDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class InputDirectory" />
  <TypeSignature Language="F#" Value="type InputDirectory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="45e20-101">ジョブのディレクトリを入力します。</span><span class="sxs-lookup"><span data-stu-id="45e20-101">Input directory for the job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputDirectory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.InputDirectory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45e20-102">InputDirectory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="45e20-102">Initializes a new instance of the InputDirectory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputDirectory (string id, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.InputDirectory.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.InputDirectory : string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.InputDirectory" Usage="new Microsoft.Azure.Management.BatchAI.Models.InputDirectory (id, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="45e20-103">入力のディレクトリの id。</span><span class="sxs-lookup"><span data-stu-id="45e20-103">The id for the input directory.</span></span></param>
        <param name="path"><span data-ttu-id="45e20-104">入力のディレクトリへのパス。</span><span class="sxs-lookup"><span data-stu-id="45e20-104">The path to the input directory.</span></span></param>
        <summary>
            <span data-ttu-id="45e20-105">InputDirectory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="45e20-105">Initializes a new instance of the InputDirectory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.InputDirectory.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.InputDirectory.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45e20-106">取得または入力ディレクトリの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="45e20-106">Gets or sets the id for the input directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="45e20-107">AZ_BATCHAI_INPUT_id 環境変数として、ジョブの利用可能な場合もなります。</span><span class="sxs-lookup"><span data-stu-id="45e20-107">It will be available for the job as an environment variable under AZ_BATCHAI_INPUT_id.</span></span> <span data-ttu-id="45e20-108">サービスは、次の環境変数も提供されます。 AZ_BATCHAI_PREV_OUTPUT_Name です。</span><span class="sxs-lookup"><span data-stu-id="45e20-108">The service will also provide the following environment variable: AZ_BATCHAI_PREV_OUTPUT_Name.</span></span> <span data-ttu-id="45e20-109">以前のエラー、それ以外の場合は nothing に設定した後、ジョブが再試行されている場合は、変数の値が表示されます。</span><span class="sxs-lookup"><span data-stu-id="45e20-109">The value of the variable will be populated if the job is being retried after a previous failure, otherwise it will be set to nothing.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.InputDirectory.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.InputDirectory.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45e20-110">取得または入力ディレクトリへのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="45e20-110">Gets or sets the path to the input directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.InputDirectory.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inputDirectory.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45e20-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="45e20-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="45e20-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="45e20-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>