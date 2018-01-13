<Type Name="IOperationDataStream" FullName="System.Fabric.IOperationDataStream">
  <TypeSignature Language="C#" Value="public interface IOperationDataStream" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationDataStream" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperationDataStream" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationDataStream" />
  <TypeSignature Language="F#" Value="type IOperationDataStream = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para> <see cref="T:System.Fabric.IOperationDataStream" />のストリームをカプセル化<see cref="T:System.Fabric.OperationData" />プライマリ レプリカとセカンダリ レプリカ間で交換されるオブジェクト。
            実装するオブジェクト<see cref="T:System.Fabric.IOperationDataStream" />コピー処理中に使用します。
            コピー コンテキスト<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドは、プライマリ レプリカとコピー状態をセカンダリ レプリカから送信される<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />メソッドの実装、<see cref="T:System.Fabric.IOperationDataStream" />インターフェイスです。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt; GetNextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.OperationData&gt; GetNextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt;" Usage="iOperationDataStream.GetNextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.MSInternal", "CA908:UseApprovedGenericsForPrecompiledAssemblies", Justification="Not precompiled assembly.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>非同期操作をキャンセルするためのメカニズムを提供します。</para>
        </param>
        <summary>
          <para>次の取得<see cref="T:System.Fabric.OperationData" />オブジェクトから、<see cref="T:System.Fabric.IOperationDataStream" />です。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Fabric.OperationData" />します。</para>
        </returns>
        <remarks>
          <para>
                Null を返すことを示す、システムに転送が完了しました。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>