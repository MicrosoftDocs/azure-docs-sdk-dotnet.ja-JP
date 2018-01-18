<Type Name="FileServerReference" FullName="Microsoft.Azure.Management.BatchAI.Models.FileServerReference">
  <TypeSignature Language="C#" Value="public class FileServerReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileServerReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.FileServerReference" />
  <TypeSignature Language="VB.NET" Value="Public Class FileServerReference" />
  <TypeSignature Language="F#" Value="type FileServerReference = class" />
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
            <span data-ttu-id="c6731-101">サービスのクラスター ノードでマウント Azure のファイル共有にできるようにするための必要な情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="c6731-101">Provides required information, for the service to be able to mount Azure FileShare on the cluster nodes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServerReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6731-102">FileServerReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6731-102">Initializes a new instance of the FileServerReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServerReference (Microsoft.Azure.Management.BatchAI.Models.ResourceId fileServer, string relativeMountPath, string sourceDirectory = null, string mountOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.ResourceId fileServer, string relativeMountPath, string sourceDirectory, string mountOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.#ctor(Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fileServer As ResourceId, relativeMountPath As String, Optional sourceDirectory As String = null, Optional mountOptions As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.FileServerReference : Microsoft.Azure.Management.BatchAI.Models.ResourceId * string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServerReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.FileServerReference (fileServer, relativeMountPath, sourceDirectory, mountOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fileServer" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="relativeMountPath" Type="System.String" />
        <Parameter Name="sourceDirectory" Type="System.String" />
        <Parameter Name="mountOptions" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fileServer"><span data-ttu-id="c6731-103">ファイル サーバー リソースへの参照。</span><span class="sxs-lookup"><span data-stu-id="c6731-103">Reference to the file server resource.</span></span></param>
        <param name="relativeMountPath"><span data-ttu-id="c6731-104">ファイル サーバーをマウントするコンピューティング ノード上の相対パスを指定します。</span><span class="sxs-lookup"><span data-stu-id="c6731-104">Specifies the relative path on the compute node where the File Server will be mounted.</span></span></param>
        <param name="sourceDirectory"><span data-ttu-id="c6731-105">マウントする必要があるファイル サーバーで、ソース ディレクトリを指定します。</span><span class="sxs-lookup"><span data-stu-id="c6731-105">Specifies the source directory in File Server that needs to be mounted.</span></span></param>
        <param name="mountOptions"><span data-ttu-id="c6731-106">ファイル サーバーのマウント オプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="c6731-106">Specifies the mount options for File Server.</span></span></param>
        <summary>
            <span data-ttu-id="c6731-107">FileServerReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6731-107">Initializes a new instance of the FileServerReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId FileServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId FileServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.FileServer" />
      <MemberSignature Language="VB.NET" Value="Public Property FileServer As ResourceId" />
      <MemberSignature Language="F#" Value="member this.FileServer : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.FileServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6731-108">取得またはファイル サーバー リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="c6731-108">Gets or sets reference to the file server resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountOptions">
      <MemberSignature Language="C#" Value="public string MountOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MountOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.MountOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property MountOptions As String" />
      <MemberSignature Language="F#" Value="member this.MountOptions : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.MountOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6731-109">取得または設定は、ファイル サーバーのマウント オプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="c6731-109">Gets or sets specifies the mount options for File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeMountPath">
      <MemberSignature Language="C#" Value="public string RelativeMountPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeMountPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.RelativeMountPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeMountPath As String" />
      <MemberSignature Language="F#" Value="member this.RelativeMountPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.RelativeMountPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativeMountPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6731-110">取得または設定は、ファイル サーバーをマウントするコンピューティング ノード上の相対パスを指定します。</span><span class="sxs-lookup"><span data-stu-id="c6731-110">Gets or sets specifies the relative path on the compute node where the File Server will be mounted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c6731-111">$AZ_BATCHAI_MOUNT_ROOT 場所の下にあるすべてのファイル共有をマウントすることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="c6731-111">Note that all file shares will be mounted under $AZ_BATCHAI_MOUNT_ROOT location.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDirectory">
      <MemberSignature Language="C#" Value="public string SourceDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.SourceDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDirectory As String" />
      <MemberSignature Language="F#" Value="member this.SourceDirectory : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.SourceDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6731-112">取得または設定は、マウントする必要があるファイル サーバーで、ソース ディレクトリを指定します。</span><span class="sxs-lookup"><span data-stu-id="c6731-112">Gets or sets specifies the source directory in File Server that needs to be mounted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c6731-113">このプロパティが指定されていない場合は、ファイル サーバーの全体がマウントされます。</span><span class="sxs-lookup"><span data-stu-id="c6731-113">If this property is not specified, the entire File Server will be mounted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileServerReference.Validate " />
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
            <span data-ttu-id="c6731-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c6731-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c6731-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6731-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>