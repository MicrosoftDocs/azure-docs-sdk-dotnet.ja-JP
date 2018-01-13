<Type Name="BackupDescription" FullName="Microsoft.ServiceFabric.Data.BackupDescription">
  <TypeSignature Language="C#" Value="public struct BackupDescription" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit BackupDescription extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupDescription" />
  <TypeSignature Language="VB.NET" Value="Public Structure BackupDescription" />
  <TypeSignature Language="F#" Value="type BackupDescription = struct" />
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
            BackupDescription には、すべてのステートフル サービス レプリカのバックアップに必要な情報が含まれています。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupDescription (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupDescription.#ctor(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupDescription : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; Microsoft.ServiceFabric.Data.BackupDescription" Usage="new Microsoft.ServiceFabric.Data.BackupDescription backupCallback" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback">
            バックアップ フォルダーが作成され、システムによってローカル設定時に呼び出されるコールバック。 このフォルダーは、ノードから移動する準備ができました。
            </param>
        <summary>
            <cref name="BackupDescription" /> 構造体の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupDescription (Microsoft.ServiceFabric.Data.BackupOption option, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Data.BackupOption option, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupDescription.#ctor(Microsoft.ServiceFabric.Data.BackupOption,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (option As BackupOption, backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupDescription : Microsoft.ServiceFabric.Data.BackupOption * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; Microsoft.ServiceFabric.Data.BackupDescription" Usage="new Microsoft.ServiceFabric.Data.BackupDescription (option, backupCallback)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option">
            <cref name="BackupOption" />バックアップします。
            </param>
        <param name="backupCallback">
            バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。
            </param>
        <summary>
            <cref name="BackupDescription" /> 構造体の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupCallback">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; BackupCallback { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; BackupCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupDescription.BackupCallback" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.BackupCallback : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.BackupDescription.BackupCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバックを取得します。
            </summary>
        <value>
            通常、バックアップ フォルダーを外部の場所にコピーするために使用するバックアップ コールバック関数。
            </value>
        <remarks>
            バックアップのコールバック関数受け取り BackupInfo とキャンセル トークンを返すをバックアップ フォルダーの処理を表すタスク。
            BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。
            False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。
            また、バックアップはマークされます失敗とします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Option">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupOption Option { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupOption Option" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupDescription.Option" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Option As BackupOption" />
      <MemberSignature Language="F#" Value="member this.Option : Microsoft.ServiceFabric.Data.BackupOption" Usage="Microsoft.ServiceFabric.Data.BackupDescription.Option" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            実行するバックアップの種類。
            </summary>
        <value>
            バックアップの種類。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>