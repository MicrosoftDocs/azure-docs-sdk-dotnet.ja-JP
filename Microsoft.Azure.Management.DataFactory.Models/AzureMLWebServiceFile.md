<Type Name="AzureMLWebServiceFile" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile">
  <TypeSignature Language="C#" Value="public class AzureMLWebServiceFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLWebServiceFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLWebServiceFile" />
  <TypeSignature Language="F#" Value="type AzureMLWebServiceFile = class" />
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
            <span data-ttu-id="8cdd2-101">Azure ML web サービスの入力/出力ファイル</span><span class="sxs-lookup"><span data-stu-id="8cdd2-101">Azure ML WebService Input/Output file</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLWebServiceFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile.#ctor" />
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
            <span data-ttu-id="8cdd2-102">AzureMLWebServiceFile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-102">Initializes a new instance of the AzureMLWebServiceFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLWebServiceFile (object filePath, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object filePath, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile.#ctor(System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (filePath As Object, linkedServiceName As LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile : obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile (filePath, linkedServiceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filePath" Type="System.Object" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
      </Parameters>
      <Docs>
        <param name="filePath"><span data-ttu-id="8cdd2-103">LinkedService で指定された Azure Blob ストレージ コンテナー名を含む相対ファイル パス。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-103">The relative file path, including container name, in the Azure Blob Storage specified by the LinkedService.</span></span>
            <span data-ttu-id="8cdd2-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="8cdd2-105">Azure ML web サービスの入力/出力ファイルが配置されている、Azure ストレージ LinkedService への参照。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-105">Reference to an Azure Storage LinkedService, where Azure ML WebService Input/Output file located.</span></span></param>
        <summary>
            <span data-ttu-id="8cdd2-106">AzureMLWebServiceFile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-106">Initializes a new instance of the AzureMLWebServiceFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public object FilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePath As Object" />
      <MemberSignature Language="F#" Value="member this.FilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cdd2-107">取得または、LinkedService で指定された Azure Blob ストレージ コンテナー名を含む、相対ファイル パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-107">Gets or sets the relative file path, including container name, in the Azure Blob Storage specified by the LinkedService.</span></span> <span data-ttu-id="8cdd2-108">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-108">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile.LinkedServiceName" />
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
            <span data-ttu-id="8cdd2-109">取得または Azure ML web サービスの入力/出力ファイルが配置されている、Azure ストレージ LinkedService への参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-109">Gets or sets reference to an Azure Storage LinkedService, where Azure ML WebService Input/Output file located.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLWebServiceFile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureMLWebServiceFile.Validate " />
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
            <span data-ttu-id="8cdd2-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8cdd2-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8cdd2-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>