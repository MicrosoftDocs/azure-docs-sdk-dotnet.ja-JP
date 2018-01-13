<Type Name="IStateProviderReplica2" FullName="Microsoft.ServiceFabric.Data.IStateProviderReplica2">
  <TypeSignature Language="C#" Value="public interface IStateProviderReplica2 : Microsoft.ServiceFabric.Data.IStateProviderReplica" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProviderReplica2 implements class Microsoft.ServiceFabric.Data.IStateProviderReplica" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProviderReplica2&#xA;Implements IStateProviderReplica" />
  <TypeSignature Language="F#" Value="type IStateProviderReplica2 = interface&#xA;    interface IStateProviderReplica" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Service Fabric サービスと対話するの信頼性の高い状態プロバイダーの複製を実装する必要がありますメソッドを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリカで復元が実行された後に呼び出される関数。
            </summary>
        <value>
            フレームワークによって、レプリカの状態が正常に復元された場合に呼び出される関数
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>