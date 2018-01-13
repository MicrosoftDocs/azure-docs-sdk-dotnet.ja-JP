<Type Name="ITrackedSaveOperation" FullName="Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation">
  <TypeSignature Language="C#" Value="public interface ITrackedSaveOperation : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrackedSaveOperation implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrackedSaveOperation&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ITrackedSaveOperation = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            保存、履歴を表し、バック グラウンド操作を定期的にコピーするには、Azure ストレージに対応する、追加 blob にファイルに追加します。
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.TimeSpan)" />
  </Docs>
  <Members>
    <Member MemberName="FlushError">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Exception&gt; FlushError;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Exception&gt; FlushError" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation.FlushError" />
      <MemberSignature Language="VB.NET" Value="Event FlushError As EventHandler(Of Exception) " />
      <MemberSignature Language="F#" Value="member this.FlushError : EventHandler&lt;Exception&gt; " Usage="member this.FlushError : System.EventHandler&lt;System.Exception&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Exception&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バック グラウンドの実行中にエラーがある場合に発生する Azure ストレージ内の blob に追加します。
            </summary>
        <remarks>
          <para>
            追加中にエラーが発生した、'最後の位置' は更新されません、ため、[次へ] のフラッシュを追加できませんでしたするデータが含まれます。
            </para>
          <para>
            エラーが発生した場合、このイベントは発生しません<see cref="M:System.IDisposable.Dispose" />。 代わりに、Dispose メソッド例外を再スロー直接です。 ここでは、バック グラウンドの追加は動作していないためにが呼び出し元のコードかどうかおよびその方法を決定するまで (たとえば、非追跡メソッドを使用して、ファイルを再度保存) フラッシュされていないデータを保存します。
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>