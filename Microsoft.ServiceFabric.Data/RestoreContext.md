<Type Name="RestoreContext" FullName="Microsoft.ServiceFabric.Data.RestoreContext">
  <TypeSignature Language="C#" Value="public struct RestoreContext" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreContext extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreContext" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreContext" />
  <TypeSignature Language="F#" Value="type RestoreContext = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <cref name="RestoreContext" />含まれています、<cref name="RestoreContext.RestoreAsync(RestoreDescription)" />を使用して、レプリカの状態をバックアップから復元をことができます。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreContext (Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.#ctor(Microsoft.ServiceFabric.Data.IStateProviderReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (stateProviderReplica As IStateProviderReplica)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreContext : Microsoft.ServiceFabric.Data.IStateProviderReplica -&gt; Microsoft.ServiceFabric.Data.RestoreContext" Usage="new Microsoft.ServiceFabric.Data.RestoreContext stateProviderReplica" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica" />
      </Parameters>
      <Docs>
        <param name="stateProviderReplica">
            <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" />信頼性の高い状態プロバイダーの複製を表すです。
            </param>
        <summary>
            <cref name="RestoreContext" /> 構造体の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync restoreDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
      </Parameters>
      <Docs>
        <param name="restoreDescription">復元要求の説明です。</param>
        <summary>
            により記述されたバックアップを復元<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />です。
            </summary>
        <returns>
            非同期の復元操作を表すタスク。
            </returns>
        <remarks>
            この API は、OnDataLossAsync メソッドから呼び出す必要があります。 によってシリアル化 API の 1 つだけでは、時間の特定の時点のレプリカあたりの転送を指定できます。
            
            この API によってスローされた例外が基になる状態プロバイダーのに応じてが異なることに注意してください。 この API は、信頼性の高いサービスや Reliable Actors サービス ファブリックにより提供される既定の状態プロバイダーにのみ適用されます用のドキュメントに記載されて現在の例外。
            <para>次の例外は、信頼性の高いサービスで呼び出されたときに、この API によってスローされた: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list></para> <para> KvsActorStateProvider にアクター サービスで、状態プロバイダー (Reliable Actors に対する既定の状態プロバイダーは、) として呼び出されたときに、この API によって次の例外がスローされます。<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            入力のバックアップ フォルダーに完全バックアップが含まれていないことを示します。
            復元するバックアップ フォルダーの 1 つの完全バックアップと増分バックアップの任意の数でなければなりません。
            </exception>
        <exception cref="T:System.ArgumentException">
            引数のいずれかが無効であることを示します。 たとえば、RestorePolicy が安全な場所が入力のバックアップ フォルダーに設定されている場合は、信頼性の高いサービスを復元する含まれている場合、状態を現在のレプリカで維持よりも古い状態のバージョン。
            
            指定した場合に、この例外をスローするアクター サービスを復元するときに<see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />が空です。
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            指定された復元ディレクトリが存在しないことを示します。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            レプリカを終了することを示します。
            </exception>
        <exception cref="T:System.InvalidOperationException">
            現在の復元操作が無効であることを示します。 たとえば、<see cref="T:System.Fabric.ServicePartitionKind" />からバックアップが作成されたパーティションの現在のパーティションを復元中のものとは異なるがします。
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            指定された復元ディレクトリ下にある予想されるバックアップ ファイルが見つからないことを示します。
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            復元操作には、予期しないエラーが発生しました。 または、バックアップ ディレクトリ内のファイル復元が無効のいずれかを示します。
            <see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティが発生したエラーの種類を示します。
            <list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>復元ディレクトリで指定されたバックアップ ファイルが不足しているファイルがいずれかまたはことを示します余分な予期しないファイル。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>メタデータ ファイル (restore.dat) 復元ディレクトリ内に存在するかが破損しているか、無効な情報が含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定されたディレクトリが壊れている、復元中です。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定したディレクトリには復元には重複しているバックアップが含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>場合<see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" />の一部として指定<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />復元に指定されたバックアップは、サービス内に現存のよりも古いデータであることを示します。</description></item></list></exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync (restoreDescription, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreDescription">復元要求の説明です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            により記述されたバックアップを復元<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />です。
            </summary>
        <returns>
            非同期の復元操作を表すタスク。
            </returns>
        <remarks>
            この API は、OnDataLossAsync メソッドから呼び出す必要があります。 によってシリアル化 API の 1 つだけでは、時間の特定の時点のレプリカあたりの転送を指定できます。
            
            この API によってスローされた例外が基になる状態プロバイダーのに応じてが異なることに注意してください。 この API は、信頼性の高いサービスや Reliable Actors サービス ファブリックにより提供される既定の状態プロバイダーにのみ適用されます用のドキュメントに記載されて現在の例外。
            <para>次の例外は、信頼性の高いサービスで呼び出されたときに、この API によってスローされた: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list></para> <para> KvsActorStateProvider にアクター サービスで、状態プロバイダー (Reliable Actors に対する既定の状態プロバイダーは、) として呼び出されたときに、この API によって次の例外がスローされます。<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            入力のバックアップ フォルダーに完全バックアップが含まれていないことを示します。
            復元するバックアップ フォルダーの 1 つの完全バックアップと増分バックアップの任意の数でなければなりません。
            </exception>
        <exception cref="T:System.ArgumentException">
            引数のいずれかが無効であることを示します。 たとえば、RestorePolicy が安全な場所が入力のバックアップ フォルダーに設定されている場合は、信頼性の高いサービスを復元する含まれている場合、状態を現在のレプリカで維持よりも古い状態のバージョン。
            
            指定した場合に、この例外をスローするアクター サービスを復元するときに<see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />が空です。
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            指定された復元ディレクトリが存在しないことを示します。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            レプリカを終了することを示します。
            </exception>
        <exception cref="T:System.InvalidOperationException">
            現在の復元操作が無効であることを示します。 たとえば、<see cref="T:System.Fabric.ServicePartitionKind" />からバックアップが作成されたパーティションの現在のパーティションを復元中のものとは異なるがします。
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            指定された復元ディレクトリ下にある予想されるバックアップ ファイルが見つからないことを示します。
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            復元操作には、予期しないエラーが発生しました。 または、バックアップ ディレクトリ内のファイル復元が無効のいずれかを示します。
            <see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティが発生したエラーの種類を示します。
            <list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>復元ディレクトリで指定されたバックアップ ファイルが不足しているファイルがいずれかまたはことを示します余分な予期しないファイル。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>メタデータ ファイル (restore.dat) 復元ディレクトリ内に存在するかが破損しているか、無効な情報が含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定されたディレクトリが壊れている、復元中です。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定したディレクトリには復元には重複しているバックアップが含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>場合<see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" />の一部として指定<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />復元に指定されたバックアップは、サービス内に現存のよりも古いデータであることを示します。</description></item></list></exception>
      </Docs>
    </Member>
  </Members>
</Type>