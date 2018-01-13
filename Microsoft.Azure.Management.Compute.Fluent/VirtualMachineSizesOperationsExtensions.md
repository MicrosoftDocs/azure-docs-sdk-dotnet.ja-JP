<Type Name="VirtualMachineSizesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineSizesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineSizesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineSizesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineSizesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineSizesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineSizesOperationsExtensions = class" />
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
            VirtualMachineSizesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineSizesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineSizesOperationsExtensions.ListAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineSizesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="location">
            どの仮想マシンのサイズと場所は、クエリを実行します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            場所でサブスクリプションのすべての利用可能な仮想マシンのサイズを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>