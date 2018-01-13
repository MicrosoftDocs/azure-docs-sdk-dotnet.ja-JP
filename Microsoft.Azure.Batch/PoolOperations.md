<Type Name="PoolOperations" FullName="Microsoft.Azure.Batch.PoolOperations">
  <TypeSignature Language="C#" Value="public class PoolOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type PoolOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure Batch アカウントにプール関連の操作を実行します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ChangeOSVersion">
      <MemberSignature Language="C#" Value="public void ChangeOSVersion (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ChangeOSVersion(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersion(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ChangeOSVersion (poolId As String, targetOSVersion As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersion : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ChangeOSVersion (poolId, targetOSVersion, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="targetOSVersion">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールのオペレーティング システムのバージョンを変更します。
            </summary>
        <remarks>
          <para>OS バージョンの変更操作中には、バッチ サービスは、コンピューティング ノードの OS バージョンを変更するプールのノードを走査します。  コンピューティング ノードを選択すると、そのノードで実行されているすべてのタスクがノードから削除され、後で (または、別の計算ノード) を再実行をキューに再登録します。  バージョンの変更が完了するまで、ノードは使用できません。</para>
          <para>操作の結果は、ノードは、サービス、OS バージョンを変更して外すように、一時的に削減プールの容量にします。 サービスが、すべての変更を回避しようとしています。 バッチはコンピューティング ノードを同時とは限りません (特にでサイズの小さいプール); の実行そのため、操作の結果に、プールがタスクの実行を一時的に利用できなくなる可能性があります。</para>
          <para>OS バージョンの変更を要求すると、プールの状態に変わります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />です。  すべてのコンピューティング ノードでは、バージョンの変更が完了したら、プールの状態に戻ります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />です。</para>
          <para>バージョンの変更が進行中、プールの中に<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" />からノードを変更する OS バージョンを反映し、<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" />ノードが変更しようとしている OS バージョンを反映します。 変更が完了したら、CurrentOSVersion はすべてのノードで実行されている OS バージョンを反映するように更新されます。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeOSVersionAsync (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ChangeOSVersionAsync(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersionAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ChangeOSVersionAsync (poolId, targetOSVersion, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="targetOSVersion">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプールのオペレーティング システムのバージョンを変更します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>OS バージョンの変更操作中には、バッチ サービスは、コンピューティング ノードの OS バージョンを変更するプールのノードを走査します。  コンピューティング ノードを選択すると、そのノードで実行されているすべてのタスクがノードから削除され、後で (または、別の計算ノード) を再実行をキューに再登録します。  バージョンの変更が完了するまで、ノードは使用できません。</para>
          <para>操作の結果は、ノードは、サービス、OS バージョンを変更して外すように、一時的に削減プールの容量にします。 サービスが、すべての変更を回避しようとしています。 バッチはコンピューティング ノードを同時とは限りません (特にでサイズの小さいプール); の実行そのため、操作の結果に、プールがタスクの実行を一時的に利用できなくなる可能性があります。</para>
          <para>OS バージョンの変更を要求すると、プールの状態に変わります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />です。  すべてのコンピューティング ノードでは、バージョンの変更が完了したら、プールの状態に戻ります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />です。</para>
          <para>バージョンの変更が進行中、プールの中に<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" />からノードを変更する OS バージョンを反映し、<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" />ノードが変更しようとしている OS バージョンを反映します。 変更が完了したら、CurrentOSVersion はすべてのノードで実行されている OS バージョンを反映するように更新されます。</para>
          <para>バージョンの変更操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateComputeNodeUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser (string poolId, string computeNodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser(string poolId, string computeNodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreateComputeNodeUser(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateComputeNodeUser (poolId As String, computeNodeId As String) As ComputeNodeUser" />
      <MemberSignature Language="F#" Value="member this.CreateComputeNodeUser : string * string -&gt; Microsoft.Azure.Batch.ComputeNodeUser" Usage="poolOperations.CreateComputeNodeUser (poolId, computeNodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">ユーザー アカウントを作成するコンピューティング ノードの id。</param>
        <summary>
            作成、<see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />を表す新しいコンピューティング ノード ユーザー アカウントに、Batch service にまだ存在しません。
            </summary>
        <returns>非結合<see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />コンピューティング ノードに追加されていない新しいユーザー アカウントを表すです。</returns>
        <remarks>新しいユーザーを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePool () As CloudPool" />
      <MemberSignature Language="F#" Value="member this.CreatePool : unit -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            バインドが、バッチ サービスでのすべてのプールに整合性のリレーションシップはありません CloudPool のインスタンスを作成します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudPool" />バッチ サービスに追加されていない新しいプールを表すです。
            Batch アカウントにプールを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.CloudServiceConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.CloudServiceConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, cloudServiceConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.CloudServiceConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="virtualMachineSize">
            プール内の仮想マシンのサイズ。  サイズの https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ を参照してください。 バッチには、ExtraSmall、A1V2 A2V2 を除くすべての Azure クラウド サービスの VM サイズがサポートしています。</param>
        <param name="cloudServiceConfiguration"><see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プールします。</param>
        <param name="targetDedicatedComputeNodes">
            専用の目的の数は、プール内のノードを計算します。
            場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。
            </param>
        <param name="targetLowPriorityComputeNodes">
            目的の優先度の低い数は、プール内のノードを計算します。
            場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。
            </param>
        <summary>
            バインドが、バッチ サービスでのすべてのプールに整合性のリレーションシップはありません CloudPool のインスタンスを作成します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudPool" />バッチ サービスに追加されていない新しいプールを表すです。
            Batch アカウントにプールを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</returns>
        <remarks>
          <para>Azure ゲスト OS ファミリの詳細については、https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/ を参照してください。 </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.VirtualMachineConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.VirtualMachineConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, virtualMachineConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.VirtualMachineConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="virtualMachineSize">プール内の仮想マシンのサイズ。 Windows サイズ https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ と linux のサイズの https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ を参照してください。
            </param>
        <param name="virtualMachineConfiguration"><see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プールします。</param>
        <param name="targetDedicatedComputeNodes">
            専用の目的の数は、プール内のノードを計算します。
            場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。
            </param>
        <param name="targetLowPriorityComputeNodes">
            目的の優先度の低い数は、プール内のノードを計算します。
            場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。
            </param>
        <summary>
            バインドが、バッチ サービスでのすべてのプールに整合性のリレーションシップはありません CloudPool のインスタンスを作成します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudPool" />バッチ サービスに追加されていない新しいプールを表すです。
            Batch アカウントにプールを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.PoolOperations" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUser">
      <MemberSignature Language="C#" Value="public void DeleteComputeNodeUser (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteComputeNodeUser(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUser(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteComputeNodeUser (poolId As String, computeNodeId As String, userName As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUser : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteComputeNodeUser (poolId, computeNodeId, userName, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">ユーザー アカウントを削除するコンピューティング ノードの id。</param>
        <param name="userName">削除するユーザー アカウントの名前。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定された計算ノードから指定されたユーザー アカウントを削除します。
            </summary>
        <remarks>
          <para>内にある場合にのみ、コンピューティング ノードからのユーザー アカウントを削除することができます、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteComputeNodeUserAsync (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteComputeNodeUserAsync(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUserAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteComputeNodeUserAsync (poolId, computeNodeId, userName, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">ユーザー アカウントを削除するコンピューティング ノードの id。</param>
        <param name="userName">削除するユーザー アカウントの名前。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定された計算ノードから指定されたユーザー アカウントを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>内にある場合にのみ、コンピューティング ノードからのユーザー アカウントを削除することができます、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFile">
      <MemberSignature Language="C#" Value="public void DeleteNodeFile (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNodeFile(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFile(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFile : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteNodeFile (poolId, computeNodeId, filePath, recursive, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="filePath">削除するファイルのパス。</param>
        <param name="recursive">
            ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。 再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。
            </param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定された計算ノードから、指定したファイルを削除します。
            </summary>
        <remarks>これは、ブロッキング操作です。  非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNodeFileAsync (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNodeFileAsync(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFileAsync : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteNodeFileAsync (poolId, computeNodeId, filePath, recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="filePath">削除するファイルのパス。</param>
        <param name="recursive">
            ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。 再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。
            </param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定された計算ノードから、指定したファイルを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>削除操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePool">
      <MemberSignature Language="C#" Value="public void DeletePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeletePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeletePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeletePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeletePool (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">削除するプールの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールを削除します。
            </summary>
        <remarks>
          <para>削除操作は、プールが削除されることを要求します。  要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" />状態です。
            バッチ サービスは、実行中のタスクをキューに再登録し、さらにクライアント操作をしなくても実際のプールの削除を実行します。</para>
          <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeletePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DeletePoolAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">削除するプールの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプールを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
          <para>削除操作は、プールが削除されることを要求します。  要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" />状態です。
            バッチ サービスは、実行中のタスクをキューに再登録し、さらにクライアント操作をしなくても実際のプールの削除を実行します。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public void DisableAutoScale (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableAutoScale(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScale(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableAutoScale (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScale : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableAutoScale (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールの自動スケーリングを無効にします。
            </summary>
        <remarks>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAutoScaleAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAutoScaleAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScaleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableAutoScaleAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DisableAutoScaleAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプールの自動スケーリングを無効にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>無効にする自動スケール操作が非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void DisableComputeNodeScheduling (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableComputeNodeScheduling(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeScheduling(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableComputeNodeScheduling (poolId As String, computeNodeId As String, disableComputeNodeSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption), Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeScheduling : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableComputeNodeScheduling (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="disableComputeNodeSchedulingOption">実行中のタスクを行うには新機能を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したコンピューティング ノードでタスクのスケジュール設定を無効にします。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeSchedulingAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableComputeNodeSchedulingAsync (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="disableComputeNodeSchedulingOption">実行中のタスクを行うには新機能を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したコンピューティング ノードでタスクのスケジュール設定を無効にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>この操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public void EnableAutoScale (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableAutoScale(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableAutoScale (poolId As String, Optional autoscaleFormula As String = null, Optional autoscaleEvaluationInterval As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableAutoScale (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="autoscaleFormula">プール内の計算ノードの必要な数の式。</param>
        <param name="autoscaleEvaluationInterval">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールの自動スケーリングを有効にします。
            </summary>
        <remarks>
          <para>数式は、プールに適用される前に、有効性に対してチェックされます。 数式が有効でない場合、例外が発生します。</para>
          <para>サイズ変更操作が、プールで進行中の場合は、プールで自動スケーリングを有効にすることはできません。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAutoScaleAsync (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAutoScaleAsync(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScaleAsync : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableAutoScaleAsync (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EnableAutoScaleAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="autoscaleFormula">プール内の計算ノードの必要な数の式。</param>
        <param name="autoscaleEvaluationInterval">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプールの自動スケーリングを有効にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>数式は、プールに適用される前に、有効性に対してチェックされます。 数式が有効でない場合、例外が発生します。</para>
          <para>サイズ変更操作が、プールで進行中の場合は、プールで自動スケーリングを有効にすることはできません。</para>
          <para>有効にする自動スケール操作が非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void EnableComputeNodeScheduling (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableComputeNodeScheduling(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableComputeNodeScheduling (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeScheduling : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableComputeNodeScheduling (poolId, computeNodeId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したコンピューティング ノードでタスクのスケジュール設定を使用できます。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeSchedulingAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeSchedulingAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableComputeNodeSchedulingAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したコンピューティング ノードでタスクのスケジュール設定を使用できます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>この操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScale(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function EvaluateAutoScale (poolId As String, autoscaleFormula As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScale : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.AutoScaleRun" Usage="poolOperations.EvaluateAutoScale (poolId, autoscaleFormula, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="autoscaleFormula">プールで評価される式です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプール内の数式のスケーリングの自動評価結果を取得します。  これは、自動スケール式を検証するため、主に、プールに、式を適用せず、結果を単純に返します。
            </summary>
        <returns>評価した結果、<paramref name="autoscaleFormula" />指定されたプールにします。</returns>
        <remarks>
          <para>数式が検証され、その結果が計算されがプールには適用されません。  適用するには、数式をプールを使用して<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</para>
          <para>このメソッドは、プールのすべての状態は変更されませんしは影響しません、<see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" />または<see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScaleAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;" Usage="poolOperations.EvaluateAutoScaleAsync (poolId, autoscaleFormula, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EvaluateAutoScaleAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="autoscaleFormula">プールで評価される式です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプール内の数式のスケーリングの自動評価結果を取得します。  これは、自動スケール式を検証するため、主に、プールに、式を適用せず、結果を単純に返します。
            </summary>
        <returns>評価した結果、<paramref name="autoscaleFormula" />指定されたプールにします。</returns>
        <remarks>
          <para>数式が検証され、その結果が計算されがプールには適用されません。  適用するには、数式をプールを使用して<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
          <para>このメソッドは、プールのすべての状態は変更されませんしは影響しません、<see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" />または<see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />です。</para>
          <para>評価操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatistics(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLifetimeStatistics (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As PoolStatistics" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatistics : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.PoolStatistics" Usage="poolOperations.GetAllLifetimeStatistics additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            現在のアカウント内のプールのすべての有効期間の概要統計情報を取得します。  
            統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのプール間で集計されます。
            </summary>
        <returns>集計されたプールの統計。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatisticsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;" Usage="poolOperations.GetAllLifetimeStatisticsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetAllLifetimeStatisticsAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            現在のアカウント内のプールのすべての有効期間の概要統計情報を取得します。
            統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのプール間で集計されます。
            </summary>
        <returns>集計されたプールの統計。</returns>
        <remarks>統計情報の取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNode GetComputeNode (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNode GetComputeNode(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNode(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetComputeNode : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.ComputeNode" Usage="poolOperations.GetComputeNode (poolId, computeNodeId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">プールから取得するコンピューティング ノードの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定された計算ノードを取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.ComputeNode" />指定された計算ノードに関する情報を格納します。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetComputeNodeAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.GetComputeNodeAsync (poolId, computeNodeId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">プールから取得するコンピューティング ノードの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定された計算ノードを取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.ComputeNode" />指定された計算ノードに関する情報を格納します。</returns>
        <remarks>ノードの取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="poolOperations.GetNodeFile (poolId, computeNodeId, filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="filePath">取得するファイルのパス。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            コンピューティング ノード上のファイルに関する情報を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.NodeFile" />ファイル、およびファイルをダウンロードして使用できるに関する情報を含む (を参照してください<see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />)。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.GetNodeFileAsync (poolId, computeNodeId, filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="filePath">取得するファイルのパス。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノード上のファイルに関する情報を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.NodeFile" />ファイル、およびファイルをダウンロードして使用できるに関する情報を含む (を参照してください<see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />)。</returns>
        <remarks>ファイルの取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool GetPool (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool GetPool(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetPool : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.GetPool (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">取得するプールの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudPool" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudPool" />指定した Azure Batch プールに関する情報を格納します。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPoolAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.GetPoolAsync (poolId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetPoolAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">取得するプールの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudPool" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudPool" />指定した Azure Batch プールに関する情報を格納します。</returns>
        <remarks>プールの取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpStream As Stream, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpStream, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</param>
        <param name="rdpStream"><see cref="T:System.IO.Stream" />に RDP ファイルの内容を書き込まれます。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したノードのリモート デスクトップ プロトコル (RDP) ファイルを取得します。
            </summary>
        <remarks>
          <para>このメソッドが閉じない、<paramref name="rdpStream" />ストリーム、およびそれでは、書き込み終了後の位置はリセットされません。
            呼び出し元の責任ストリームを閉じ、または必要な場合は、位置をリセットします。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpFileNameToCreate As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</param>
        <param name="rdpFileNameToCreate">RDP ファイルを作成するファイルのパス。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したノードのリモート デスクトップ プロトコル ファイルを取得します。
            </summary>
        <remarks>
          <para>ファイルを指定して場合<paramref name="rdpFileNameToCreate" />が既に存在するが上書きされます。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpStream, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</param>
        <param name="rdpStream"><see cref="T:System.IO.Stream" />に RDP ファイルの内容を書き込まれます。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したノードのリモート デスクトップ プロトコル (RDP) ファイルを取得します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>このメソッドが閉じない、<paramref name="rdpStream" />ストリーム、およびそれでは、書き込み終了後の位置はリセットされません。
            呼び出し元の責任ストリームを閉じ、または必要な場合は、位置をリセットします。</para>
          <para>RDP ファイルの取得操作は非同期的に実行されます。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</param>
        <param name="rdpFileNameToCreate">RDP ファイルを作成するファイルのパス。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したノードのリモート デスクトップ プロトコル ファイルを取得します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>ファイルを指定して場合<paramref name="rdpFileNameToCreate" />が既に存在するが上書きされます。</para>
          <para>RDP ファイルの取得操作は非同期的に実行されます。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemoteLoginSettings (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As RemoteLoginSettings" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettings : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.RemoteLoginSettings" Usage="poolOperations.GetRemoteLoginSettings (poolId, computeNodeId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RemoteLoginSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> GetRDPFileAsync/GetRDPFile のいずれかのプロパティを使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettingsAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;" Usage="poolOperations.GetRemoteLoginSettingsAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>リモート ログインの設定の取得操作は非同期的に実行されます。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> GetRDPFileAsync/GetRDPFile のいずれかのプロパティを使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListComputeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListComputeNodes(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListComputeNodes : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.ListComputeNodes (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、<see cref="T:Microsoft.Azure.Batch.ComputeNode">コンピューティング ノード</see>の指定したプールします。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />非同期的または同期的にコンピューティング ノードの列挙を使用できます。</returns>
        <remarks>このメソッドがすぐに戻るノードは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。ノードは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeAgentSkus(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeAgentSkus : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;" Usage="poolOperations.ListNodeAgentSkus (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            Batch Service によってサポートされているノード エージェント Sku 値を列挙します。 
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ノード エージェント sku 値を非同期的または同期的に列挙を使用できます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (string poolId, string computeNodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeFiles(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.ListNodeFiles (poolId, computeNodeId, recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">コンピューティング ノードの id。</param>
        <param name="recursive">True の場合、再帰的には、コンピューティング ノードのすべてのファイルを列挙します。 False の場合は、コンピューティング ノードのルート ディレクトリ内のファイルのみを列挙します。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            指定された計算ノード上のファイルを列挙します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ファイルを列挙する非同期的または同期的に使用できます。</returns>
        <remarks>このメソッドがすぐに戻るファイル データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。ファイル データは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt; ListPools (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; ListPools(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPools : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.ListPools (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、<see cref="T:Microsoft.Azure.Batch.CloudPool">プール</see>Batch アカウントにします。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的には、プールを列挙を使用できます。</returns>
        <remarks>このメソッドがすぐに戻るプールは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。プールは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPoolUsageMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPoolUsageMetrics(System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPoolUsageMetrics : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;" Usage="poolOperations.ListPoolUsageMetrics (startTime, endTime, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime">このエントリに含まれる集計範囲の開始時刻です。</param>
        <param name="endTime">このエントリの集計間隔の終了時刻です。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            プールの使用状況メトリックを列挙します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />メトリックを非同期的または同期的に列挙を使用できます。</returns>
        <remarks>このメソッドがすぐに戻るメトリック データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。メトリック データは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public void Reboot (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reboot(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reboot(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reboot (poolId As String, computeNodeId As String, Optional rebootOption As Nullable(Of ComputeNodeRebootOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reboot : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reboot (poolId, computeNodeId, rebootOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">再起動してコンピューティング ノードの id。</param>
        <param name="rebootOption">ノードを再起動して、実行中のタスクの処理方法を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定された計算ノードを再起動します。
            </summary>
        <remarks>
          <para>コンピューティング ノードを再起動するにあるときにのみ、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RebootAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RebootAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RebootAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RebootAsync (poolId, computeNodeId, rebootOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">再起動してコンピューティング ノードの id。</param>
        <param name="rebootOption">ノードを再起動して、実行中のタスクの処理方法を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定された計算ノードを再起動します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>コンピューティング ノードを再起動するにあるときにのみ、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</para>
          <para>再起動操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reimage(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reimage(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage (poolId As String, computeNodeId As String, Optional reimageOption As Nullable(Of ComputeNodeReimageOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reimage : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reimage (poolId, computeNodeId, reimageOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">再イメージ化にコンピューティング ノードの id。</param>
        <param name="reimageOption">ノードを再イメージ化する場合と、実行中のタスクの処理方法を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したコンピューティング ノードで、オペレーティング システムを再インストールします。
            </summary>
        <remarks>
          <para>内にある場合にのみ、コンピューティング ノードを再イメージ化できる、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReimageAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReimageAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ReimageAsync (poolId, computeNodeId, reimageOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">コンピューティング ノードを含むプールの id。</param>
        <param name="computeNodeId">再イメージ化にコンピューティング ノードの id。</param>
        <param name="reimageOption">ノードを再イメージ化する場合と、実行中のタスクの処理方法を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したコンピューティング ノードで、オペレーティング システムを再インストールします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>内にある場合にのみ、コンピューティング ノードを再イメージ化できる、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</para>
          <para>再イメージ化操作が非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNode"><see cref="T:Microsoft.Azure.Batch.ComputeNode" />をプールから削除します。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <remarks>
          <para>使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />オーバー ロードします。</para>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodes As IEnumerable(Of ComputeNode), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodes"><see cref="T:Microsoft.Azure.Batch.ComputeNode">コンピューティング ノード</see>をプールから削除します。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <remarks>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeIds As IEnumerable(Of String), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeIds">プールから削除するコンピューティング ノードの id。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <remarks>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">プールから削除するコンピューティング ノードの id。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <remarks>
          <para>使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />オーバー ロードします。</para>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNode"><see cref="T:Microsoft.Azure.Batch.ComputeNode" />をプールから削除します。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />オーバー ロードします。</para>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveFromPoolAsync (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeId">プールから削除するコンピューティング ノードの id。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />オーバー ロードします。</para>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;RemoveFromPoolAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodes"><see cref="T:Microsoft.Azure.Batch.ComputeNode">コンピューティング ノード</see>をプールから削除します。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="computeNodeIds">プールから削除するコンピューティング ノードの id。</param>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">プールから計算ノードの削除のためのタイムアウトを指定します。 既定値は、15 分です。 最小値は、5 分です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプールから指定された計算ノードを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。 プールは既にサイズ変更、例外が発生します。</para>
          <para>プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePool">
      <MemberSignature Language="C#" Value="public void ResizePool (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResizePool(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePool(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResizePool (poolId As String, Optional targetDedicatedComputeNodes As Nullable(Of Integer) = null, Optional targetLowPriorityComputeNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ResizePool : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ResizePool (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="targetDedicatedComputeNodes">
            専用の目的の数は、プール内のノードを計算します。
            少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。
            </param>
        <param name="targetLowPriorityComputeNodes">
            目的の優先度の低い数は、プール内のノードを計算します。
            少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。
            </param>
        <param name="resizeTimeout">プールにコンピューティング ノードの割り当てまたはプールから、コンピューティング ノードの削除のタイムアウトです。 プールに達していない目標サイズこの時間以降後、サイズ変更は停止されます。 既定では 15 分です。</param>
        <param name="deallocationOption">
            プールのサイズが減少している場合は、処理する方法、既に実行中のタスクし、プールからそれらを実行してノードをいつ削除することがありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したプールのサイズを変更します。
            </summary>
        <remarks>
          <para>サイズ変更操作は、プールのサイズが変更できることを要求します。  要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />割り当ての状態。
            バッチ サービスは、さらにクライアント操作をしなくても、実際のサイズ変更を実行し、割り当て状態を設定<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />1 回を完了します。</para>
          <para>
            プールのサイズを変更することができますのみときにその<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。
            自動スケーリング用に構成されているプールのサイズを変更することはできません (つまり、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />プールのプロパティが true)。
            プール サイズを小さくした場合、Batch service を削除するノードを選択します。  特定のノードを削除するには、呼び出す<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。
            </para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResizePoolAsync (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResizePoolAsync(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResizePoolAsync : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ResizePoolAsync (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="targetDedicatedComputeNodes">
            専用の目的の数は、プール内のノードを計算します。
            少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。
            </param>
        <param name="targetLowPriorityComputeNodes">
            目的の優先度の低い数は、プール内のノードを計算します。
            少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。
            </param>
        <param name="resizeTimeout">プールにコンピューティング ノードの割り当てまたはプールから、コンピューティング ノードの削除のタイムアウトです。 プールに達していない目標サイズこの時間以降後、サイズ変更は停止されます。 既定では 15 分です。</param>
        <param name="deallocationOption">
            プールのサイズが減少している場合は、処理する方法、既に実行中のタスクし、プールからそれらを実行してノードをいつ削除することがありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したプールのサイズを変更します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>サイズ変更操作は、プールのサイズが変更できることを要求します。  要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />割り当ての状態。
            バッチ サービスは、さらにクライアント操作をしなくても、実際のサイズ変更を実行し、割り当て状態を設定<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />1 回を完了します。</para>
          <para>
            プールのサイズを変更することができますのみときにその<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。
            自動スケーリング用に構成されているプールのサイズを変更することはできません (つまり、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />プールのプロパティが true)。
            プール サイズを小さくした場合、Batch service を削除するノードを選択します。  特定のノードを削除するには、呼び出す<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。
            </para>
          <para>サイズ変更操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePool">
      <MemberSignature Language="C#" Value="public void StopResizePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void StopResizePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopResizePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.StopResizePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.StopResizePool (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <summary>
            サイズ変更操作をプールを停止します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>
            この操作は、プールで進行中のサイズ変更操作を停止します。  プールのサイズは、停止操作が行われるときにノードの数に安定します。  停止操作で、プール<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />最初に変更<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" />し<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />です。
            </para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopResizePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopResizePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopResizePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.StopResizePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">プールの ID。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            サイズ変更操作をプールを停止します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>
            この操作は、プールで進行中のサイズ変更操作を停止します。  プールのサイズは、停止操作が行われるときにノードの数に安定します。  停止操作で、プール<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />最初に変更<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" />し<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />です。
            </para>
          <para>停止では、操作の実行が非同期的にサイズ変更します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>