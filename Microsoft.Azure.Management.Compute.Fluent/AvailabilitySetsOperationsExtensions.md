<Type Name="AvailabilitySetsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AvailabilitySetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AvailabilitySetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AvailabilitySetsOperationsExtensions = class" />
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
            AvailabilitySetsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, availabilitySetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="availabilitySetName">To be added.</param>
        <param name="parameters">
            パラメーターは、可用性セットの作成操作に指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または可用性セットを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="availabilitySetName">
            可用性セットの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            可用性セットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.GetAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="availabilitySetName">
            可用性セットの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            可用性セットに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
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
            リソース グループ内のすべての可用性セットを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync (this Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations operations, string resourceGroupName, string availabilitySetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAvailableSizesAsync(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizesAsync : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions.ListAvailableSizesAsync (operations, resourceGroupName, availabilitySetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.AvailabilitySetsOperationsExtensions/&lt;ListAvailableSizesAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="availabilitySetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="availabilitySetName">
            可用性セットの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の可用性セットで、新しいバーチャル マシンを作成するために使用するすべての利用可能な仮想マシンのサイズを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>