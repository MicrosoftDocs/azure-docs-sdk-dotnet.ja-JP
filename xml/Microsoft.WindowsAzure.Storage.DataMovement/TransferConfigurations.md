<Type Name="TransferConfigurations" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations">
  <TypeSignature Language="C#" Value="public class TransferConfigurations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferConfigurations extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferConfigurations" />
  <TypeSignature Language="F#" Value="type TransferConfigurations = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2988d-101">TransferConfigurations クラスです。</span><span class="sxs-lookup"><span data-stu-id="2988d-101">TransferConfigurations class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2988d-102"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2988d-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockSize">
      <MemberSignature Language="C#" Value="public int BlockSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BlockSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockSize As Integer" />
      <MemberSignature Language="F#" Value="member this.BlockSize : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2988d-103">取得または転送に使用する Windows Azure ストレージれる blob をブロックするブロック サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="2988d-103">Gets or sets the BlockSize to use for Windows Azure Storage transfers to block blob(s).</span></span> <span data-ttu-id="2988d-104">4 MB ~ 100 MB にするおよび倍数である必要がありますは 4 MB です。</span><span class="sxs-lookup"><span data-stu-id="2988d-104">It must be between 4MB and 100MB and be multiple of 4MB.</span></span>
            
            <span data-ttu-id="2988d-105">現時点では、ブロック blob の最大ブロック数は、50000 に制限されます。</span><span class="sxs-lookup"><span data-stu-id="2988d-105">Currently, the max block count of a block blob is limited to 50000.</span></span>
            <span data-ttu-id="2988d-106">転送サイズの大きなファイルおよび指定されたブロック サイズより小さい場合の最小値 (サイズ/50000) がありますにリセットされますは、最小値および複数より大きい値はこのファイルの 4 MB です。</span><span class="sxs-lookup"><span data-stu-id="2988d-106">When transfering a big file and the BlockSize provided is smaller than the minimum value - (size/50000), it'll be reset to a value which is greater than the minimum value and multiple of 4MB for this file.</span></span>
            </summary>
        <value><span data-ttu-id="2988d-107">Windows Azure ストレージの転送に使用するブロック サイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="2988d-107">BlockSize to use for Windows Azure Storage transfers.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperations">
      <MemberSignature Language="C#" Value="public int ParallelOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ParallelOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperations As Integer" />
      <MemberSignature Language="F#" Value="member this.ParallelOperations : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2988d-108">取得または設定数の作業を示す値の項目を同時に処理します。</span><span class="sxs-lookup"><span data-stu-id="2988d-108">Gets or sets a value indicating how many work items to process concurrently.</span></span> <span data-ttu-id="2988d-109">ダウンロードや、単一の blob のアップロードは、大量の作業項目で構成できます。</span><span class="sxs-lookup"><span data-stu-id="2988d-109">Downloading or uploading a single blob can consist of a large number of work items.</span></span>
            </summary>
        <value><span data-ttu-id="2988d-110">同時に処理する作業項目の数。</span><span class="sxs-lookup"><span data-stu-id="2988d-110">How many work items to process concurrently.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentPrefix">
      <MemberSignature Language="C#" Value="public string UserAgentPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentPrefix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentPrefix : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2988d-111">取得またはユーザー エージェントのプレフィックスの設定</span><span class="sxs-lookup"><span data-stu-id="2988d-111">Gets or sets the user agent prefix</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>