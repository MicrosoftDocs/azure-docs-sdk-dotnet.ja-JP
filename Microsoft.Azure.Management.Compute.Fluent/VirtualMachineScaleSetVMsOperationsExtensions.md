<Type Name="VirtualMachineScaleSetVMsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineScaleSetVMsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            VirtualMachineScaleSetVMsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の特定の仮想マシンの割り当てを解除します。 仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。 料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットから仮想マシンを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            (停止) 仮想マシンに VM スケール セットの電源を切ります。 リソースがまだアタッチされているリソースには料金が取得することに注意してください。 代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAllAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスク、仮想マシン スケール セットのインスタンス。 この操作は、管理対象ディスクに対してのみサポートされます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            (オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginRestartAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の仮想マシンを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginStartAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の仮想マシンを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeallocateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の特定の仮想マシンの割り当てを解除します。 仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。 料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットから仮想マシンを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットから仮想マシンを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt; GetInstanceViewAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt; GetInstanceViewAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetInstanceViewAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetInstanceViewAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットから仮想マシンの状態を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; odataQuery = null, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; odataQuery, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualMachineScaleSetName, odataQuery, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualMachineScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            リストのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットのすべての仮想マシンの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットのすべての仮想マシンの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;PowerOffAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            (停止) 仮想マシンに VM スケール セットの電源を切ります。 リソースがまだアタッチされているリソースには料金が取得することに注意してください。 代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAllAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスク、仮想マシン スケール セットのインスタンス。 この操作は、管理対象ディスクに対してのみサポートされます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            (オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;RestartAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の仮想マシンを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;StartAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">
            VM スケール セットの名前。
            </param>
        <param name="instanceId">
            仮想マシンのインスタンス ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の仮想マシンを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>