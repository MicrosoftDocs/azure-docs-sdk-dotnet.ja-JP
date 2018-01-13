<Type Name="VirtualMachineScaleSetsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineScaleSetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineScaleSetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineScaleSetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetsOperationsExtensions = class" />
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
            VirtualMachineScaleSetsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmScaleSetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="parameters">
            小数点以下桁数は、オブジェクトを設定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または、VM スケール セットを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の特定の仮想マシンの割り当てを解除します。 仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。 この仮想マシン スケール セットの割り当てを解除するコンピューティング リソースの料金はかかりません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
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
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteInstancesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteInstancesAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteInstancesAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginDeleteInstancesAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteInstancesAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginDeleteInstancesAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginDeleteInstancesAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の仮想マシンを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            電源をオフ (停止) VM スケール セット内の 1 つまたは複数の仮想マシン。 リソースがまだアタッチされているリソースには料金が取得することに注意してください。
            代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginReimageAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginReimageAllAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="instanceIds">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginReimageAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginReimageAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="instanceIds">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginRestartAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の 1 つまたは複数の仮想マシンを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginStartAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の 1 つまたは複数の仮想マシンを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, vmScaleSetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateInstancesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginUpdateInstancesAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginUpdateInstancesAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginUpdateInstancesAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateInstancesAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.BeginUpdateInstancesAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;BeginUpdateInstancesAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケールで最新の SKU に 1 つまたは複数の仮想マシンの設定のアップグレードは、モデルを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmScaleSetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="parameters">
            小数点以下桁数は、オブジェクトを設定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または、VM スケール セットを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;DeallocateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の特定の仮想マシンの割り当てを解除します。 仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。 この仮想マシン スケール セットの割り当てを解除するコンピューティング リソースの料金はかかりません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
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
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstancesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteInstancesAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteInstancesAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.DeleteInstancesAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteInstancesAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.DeleteInstancesAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;DeleteInstancesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の仮想マシンを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.GetAsync (operations, resourceGroupName, vmScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
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
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            仮想マシン スケール セットに関する情報を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInstanceViewInner&gt; GetInstanceViewAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInstanceViewInner&gt; GetInstanceViewAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.GetInstanceViewAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetInstanceViewAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInstanceViewInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.GetInstanceViewAsync (operations, resourceGroupName, vmScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;GetInstanceViewAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInstanceViewInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
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
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            状態の VM スケール セットのインスタンスを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ListAllAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            関連付けられているリソース グループに関係なく、サブスクリプション内のすべての VM スケール セットの一覧を取得します。 応答で nextLink プロパティを使用して、VM スケール セットの次のページを取得します。 NextLink が null ではすべての VM スケール セットをフェッチするまで、この操作を行います。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ListAllNextAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
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
            関連付けられているリソース グループに関係なく、サブスクリプション内のすべての VM スケール セットの一覧を取得します。 応答で nextLink プロパティを使用して、VM スケール セットの次のページを取得します。 NextLink が null ではすべての VM スケール セットをフェッチするまで、この操作を行います。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループに属するすべての VM スケールの一覧のセットを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
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
            リソース グループに属するすべての VM スケールの一覧のセットを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt; ListSkusAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt; ListSkusAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListSkusAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListSkusAsync (operations, resourceGroupName, vmScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ListSkusAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
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
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            各 SKU に対して許可される最小値と最大の VM インスタンスを含む、VM スケール セットの使用可能な Sku の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt; ListSkusNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt; ListSkusNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListSkusNextAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusNextAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ListSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ListSkusNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
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
            各 SKU に対して許可される最小値と最大の VM インスタンスを含む、VM スケール セットの使用可能な Sku の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;PowerOffAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            電源をオフ (停止) VM スケール セット内の 1 つまたは複数の仮想マシン。 リソースがまだアタッチされているリソースには料金が取得することに注意してください。
            代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ReimageAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ReimageAllAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="instanceIds">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ReimageAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.ReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;ReimageAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="instanceIds">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.RestartAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;RestartAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の 1 つまたは複数の仮想マシンを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.StartAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;StartAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケール セット内の 1 つまたは複数の仮想マシンを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.UpdateAsync (operations, resourceGroupName, vmScaleSetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmScaleSetName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateInstancesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; UpdateInstancesAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; UpdateInstancesAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations operations, string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.UpdateInstancesAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateInstancesAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions.UpdateInstancesAsync (operations, resourceGroupName, vmScaleSetName, instanceIds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetsOperationsExtensions/&lt;UpdateInstancesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
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
        <param name="instanceIds">
            仮想マシン スケール セットのインスタンス id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VM スケールで最新の SKU に 1 つまたは複数の仮想マシンの設定のアップグレードは、モデルを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>