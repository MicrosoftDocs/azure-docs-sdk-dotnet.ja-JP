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
      <para>プロセスの進行状況に関する情報をイメージ ストア操作から進行中のハンドラーを実装する必要がある動作を定義します。</para>
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
          <para>(など、アプリケーション パッケージのアップロードし、ダウンロードの進行状況) のポーリングを使用するいくつかの詳細の進捗状況情報は公開され、間隔を取得します。 0 を返すと、2 秒のシステムの既定値が使用されます。</para>
        </summary>
        <returns>
          <para><see cref="T:System.TimeSpan" />進行状況の更新間隔を表すです。</para>
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
        <param name="completedItems">完了した作業項目の数。</param>
        <param name="totalItems">作業項目の合計数。</param>
        <param name="itemType">それぞれの測定単位の作業項目。</param>
        <summary>
          <para>現在の操作の進行状況をレポートします。</para>
        </summary>
        <remarks>常に、項目の合計数は、操作の先頭に既知であるは保証されません。 場合によってより多くの作業が処理中に検出された場合、この値は増やすことができます。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>