<Type Name="StoreOperationsBatch" FullName="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch">
  <TypeSignature Language="C#" Value="public sealed class StoreOperationsBatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StoreOperationsBatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StoreOperationsBatch" />
  <TypeSignature Language="F#" Value="type StoreOperationsBatch = class" />
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
            <span data-ttu-id="4eb59-101">一連のサーバー プッシュまたはプルなど、1 つのアクションのコンテキスト内で発生した操作を表します。</span><span class="sxs-lookup"><span data-stu-id="4eb59-101">Represents a series of operations that happened within the context of a single action such as a server push or pull.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoreOperationsBatch (string batchId, Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string batchId, valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.#ctor(System.String,Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (batchId As String, source As StoreOperationSource)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch : string * Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource -&gt; Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch" Usage="new Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch (batchId, source)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="batchId" Type="System.String" />
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource" />
      </Parameters>
      <Docs>
        <param name="batchId">To be added.</param>
        <param name="source">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchId">
      <MemberSignature Language="C#" Value="public string BatchId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BatchId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.BatchId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BatchId As String" />
      <MemberSignature Language="F#" Value="member this.BatchId : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.BatchId" />
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
            <span data-ttu-id="4eb59-102">この操作が属するバッチの ID。</span><span class="sxs-lookup"><span data-stu-id="4eb59-102">The ID of the batch this operation belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationCountByKind">
      <MemberSignature Language="C#" Value="public int GetOperationCountByKind (Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind operationKind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 GetOperationCountByKind(valuetype Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind operationKind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.GetOperationCountByKind(Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOperationCountByKind (operationKind As LocalStoreOperationKind) As Integer" />
      <MemberSignature Language="F#" Value="member this.GetOperationCountByKind : Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind -&gt; int" Usage="storeOperationsBatch.GetOperationCountByKind operationKind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationKind" Type="Microsoft.WindowsAzure.MobileServices.Sync.LocalStoreOperationKind" />
      </Parameters>
      <Docs>
        <param name="operationKind"><span data-ttu-id="4eb59-103">操作の種類。</span><span class="sxs-lookup"><span data-stu-id="4eb59-103">The kind of operation.</span></span></param>
        <summary>
            <span data-ttu-id="4eb59-104">このバッチ内で実行する指定された演算の種類に一致する操作の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="4eb59-104">Gets the number of operations matching the provided operation kind executed within this batch.</span></span>
            </summary>
        <returns><span data-ttu-id="4eb59-105">指定された数と一致する操作の数。</span><span class="sxs-lookup"><span data-stu-id="4eb59-105">The number of operations matching the provided count.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationCount">
      <MemberSignature Language="C#" Value="public int OperationCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 OperationCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.OperationCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationCount As Integer" />
      <MemberSignature Language="F#" Value="member this.OperationCount : int" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.OperationCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4eb59-106">このバッチ内で実行される操作の数。</span><span class="sxs-lookup"><span data-stu-id="4eb59-106">The number of operations executed within this batch.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As StoreOperationSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationsBatch.Source" />
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
            <span data-ttu-id="4eb59-107">この操作がトリガーされたソースを示します。</span><span class="sxs-lookup"><span data-stu-id="4eb59-107">Describes the source this operation was triggered from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>