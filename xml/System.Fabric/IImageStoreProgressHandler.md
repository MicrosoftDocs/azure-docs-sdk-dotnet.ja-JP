<Type Name="IImageStoreProgressHandler" FullName="System.Fabric.IImageStoreProgressHandler">
  <TypeSignature Language="C#" Value="public interface IImageStoreProgressHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IImageStoreProgressHandler" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IImageStoreProgressHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IImageStoreProgressHandler" />
  <TypeSignature Language="F#" Value="type IImageStoreProgressHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="1c68b-101">プロセスの進行状況に関する情報をイメージ ストア操作から進行中のハンドラーを実装する必要がある動作を定義します。</span><span class="sxs-lookup"><span data-stu-id="1c68b-101">Defines the behavior that a progress handler must implement to process progress information from Image Store operations</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetUpdateInterval">
      <MemberSignature Language="C#" Value="public TimeSpan GetUpdateInterval ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype System.TimeSpan GetUpdateInterval() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IImageStoreProgressHandler.GetUpdateInterval" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUpdateInterval () As TimeSpan" />
      <MemberSignature Language="F#" Value="abstract member GetUpdateInterval : unit -&gt; TimeSpan" Usage="iImageStoreProgressHandler.GetUpdateInterval " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="1c68b-102">(など、アプリケーション パッケージのアップロードし、ダウンロードの進行状況) のポーリングを使用するいくつかの詳細の進捗状況情報は公開され、間隔を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c68b-102">Retrieves the interval at which progress information is published for some details that use polling (such as application package upload and download progress).</span></span> <span data-ttu-id="1c68b-103">0 を返すと、2 秒のシステムの既定値が使用されます。</span><span class="sxs-lookup"><span data-stu-id="1c68b-103">Returning zero will use the system default of 2 seconds.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1c68b-104"><see cref="T:System.TimeSpan" />進行状況の更新間隔を表すです。</span><span class="sxs-lookup"><span data-stu-id="1c68b-104">The <see cref="T:System.TimeSpan" /> representing the progress update interval.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateProgress">
      <MemberSignature Language="C#" Value="public void UpdateProgress (long completedItems, long totalItems, System.Fabric.ProgressUnitType itemType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateProgress(int64 completedItems, int64 totalItems, valuetype System.Fabric.ProgressUnitType itemType) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IImageStoreProgressHandler.UpdateProgress(System.Int64,System.Int64,System.Fabric.ProgressUnitType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateProgress (completedItems As Long, totalItems As Long, itemType As ProgressUnitType)" />
      <MemberSignature Language="F#" Value="abstract member UpdateProgress : int64 * int64 * System.Fabric.ProgressUnitType -&gt; unit" Usage="iImageStoreProgressHandler.UpdateProgress (completedItems, totalItems, itemType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="completedItems" Type="System.Int64" />
        <Parameter Name="totalItems" Type="System.Int64" />
        <Parameter Name="itemType" Type="System.Fabric.ProgressUnitType" />
      </Parameters>
      <Docs>
        <param name="completedItems"><span data-ttu-id="1c68b-105">完了した作業項目の数。</span><span class="sxs-lookup"><span data-stu-id="1c68b-105">The number of completed work items.</span></span></param>
        <param name="totalItems"><span data-ttu-id="1c68b-106">作業項目の合計数。</span><span class="sxs-lookup"><span data-stu-id="1c68b-106">The total number of work items.</span></span></param>
        <param name="itemType"><span data-ttu-id="1c68b-107">それぞれの測定単位の作業項目。</span><span class="sxs-lookup"><span data-stu-id="1c68b-107">The unit of measurement for each work item.</span></span></param>
        <summary>
          <para><span data-ttu-id="1c68b-108">現在の操作の進行状況をレポートします。</span><span class="sxs-lookup"><span data-stu-id="1c68b-108">Reports the progress of the current operation</span></span></para>
        </summary>
        <remarks><span data-ttu-id="1c68b-109">常に、項目の合計数は、操作の先頭に既知であるは保証されません。</span><span class="sxs-lookup"><span data-stu-id="1c68b-109">The total number of items is not always guaranteed to be known at the beginning of the operation.</span></span> <span data-ttu-id="1c68b-110">場合によってより多くの作業が処理中に検出された場合、この値は増やすことができます。</span><span class="sxs-lookup"><span data-stu-id="1c68b-110">In some cases, this value can increase if more work is discovered during processing.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>