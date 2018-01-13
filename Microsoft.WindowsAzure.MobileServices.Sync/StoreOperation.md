<Type Name="StoreOperation" FullName="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation">
  <TypeSignature Language="C#" Value="public class StoreOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StoreOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class StoreOperation" />
  <TypeSignature Language="F#" Value="type StoreOperation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68640-101">ローカル データ ストアに対して操作を表します。</span><span class="sxs-lookup"><span data-stu-id="68640-101">Represents an operation against the local data store.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoreOperation (string tableName, string recordId, Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind kind, Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource source, string batchId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tableName, string recordId, valuetype Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind kind, valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource source, string batchId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.#ctor(System.String,System.String,Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind,Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableName As String, recordId As String, kind As LocalStoreOperationKind, source As StoreOperationSource, batchId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation : string * string * Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind * Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource * string -&gt; Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation" Usage="new Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation (tableName, recordId, kind, source, batchId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="recordId" Type="System.String" />
        <Parameter Name="kind" Type="Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind" />
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource" />
        <Parameter Name="batchId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="68640-102">この操作の対象となっているテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="68640-102">The name of the table that is the target of this operation.</span></span></param>
        <param name="recordId"><span data-ttu-id="68640-103">ターゲットのレコードの識別子です。</span><span class="sxs-lookup"><span data-stu-id="68640-103">The target record identifier.</span></span></param>
        <param name="kind"><span data-ttu-id="68640-104">操作の種類。</span><span class="sxs-lookup"><span data-stu-id="68640-104">The kind of operation.</span></span></param>
        <param name="source"><span data-ttu-id="68640-105">この操作をトリガーしたソースです。</span><span class="sxs-lookup"><span data-stu-id="68640-105">The source that triggered this operation.</span></span></param>
        <param name="batchId"><span data-ttu-id="68640-106">この操作が属するバッチの id。</span><span class="sxs-lookup"><span data-stu-id="68640-106">The id of the batch this operation belongs to.</span></span></param>
        <summary>
            <span data-ttu-id="68640-107">インスタンスを作成<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="68640-107">Creates an instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchId">
      <MemberSignature Language="C#" Value="public string BatchId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BatchId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.BatchId" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchId As String" />
      <MemberSignature Language="F#" Value="member this.BatchId : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.BatchId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68640-108">この操作が属するバッチの ID。</span><span class="sxs-lookup"><span data-stu-id="68640-108">The ID of the batch this operation belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As LocalStoreOperationKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68640-109">操作の種類。</span><span class="sxs-lookup"><span data-stu-id="68640-109">The kind of operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecordId">
      <MemberSignature Language="C#" Value="public string RecordId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecordId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.RecordId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecordId As String" />
      <MemberSignature Language="F#" Value="member this.RecordId : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.RecordId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68640-110">レコードの ID がこの操作の対象となった、この操作します。</span><span class="sxs-lookup"><span data-stu-id="68640-110">The ID of the record this operation that was the target of this operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As StoreOperationSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68640-111">この操作がトリガーされたソースを示します。</span><span class="sxs-lookup"><span data-stu-id="68640-111">Describes the source this operation was triggered from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperation.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68640-112">この操作が実行されたテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="68640-112">The name of the table this operation was executed against.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>