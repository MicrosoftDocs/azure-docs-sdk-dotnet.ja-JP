<Type Name="VirtualNetworkGatewayConnectionsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewayConnectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewayConnectionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            VirtualNetworkGatewayConnectionsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As VirtualNetworkGatewayConnection) As VirtualNetworkGatewayConnection" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            パラメーターが作成または更新仮想ネットワーク ゲートウェイの接続操作を指定します。
            </param>
        <summary>
            作成するか、指定されたリソース グループ内の仮想ネットワーク ゲートウェイ接続を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            パラメーターが作成または更新仮想ネットワーク ゲートウェイの接続操作を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたリソース グループ内の仮想ネットワーク ゲートウェイ接続を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDelete (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <summary>
            指定された仮想ネットワーク ゲートウェイの接続を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された仮想ネットワーク ゲートウェイの接続を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey BeginResetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey BeginResetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginResetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionResetSharedKey) As ConnectionResetSharedKey" />
      <MemberSignature Language="F#" Value="static member BeginResetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続は、共有キーの名前をリセットします。
            </param>
        <param name="parameters">
            開始する指定されたパラメーターは、ネットワーク リソース プロバイダーを仮想ネットワーク ゲートウェイ接続の共有のキー操作をリセットします。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionResetSharedKey 操作は、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーをリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; BeginResetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; BeginResetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginResetSharedKeyAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続は、共有キーの名前をリセットします。
            </param>
        <param name="parameters">
            開始する指定されたパラメーターは、ネットワーク リソース プロバイダーを仮想ネットワーク ゲートウェイ接続の共有のキー操作をリセットします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionResetSharedKey 操作は、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーをリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionSharedKey BeginSetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey BeginSetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginSetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionSharedKey) As ConnectionSharedKey" />
      <MemberSignature Language="F#" Value="static member BeginSetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続名です。
            </param>
        <param name="parameters">
            仮想ネットワークの設定を開始ゲートウェイ接続共有キー操作 throughNetwork リソース プロバイダーに渡されるパラメーター。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionSharedKey の Put 操作では、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; BeginSetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; BeginSetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginSetSharedKeyAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続名です。
            </param>
        <param name="parameters">
            仮想ネットワークの設定を開始ゲートウェイ接続共有キー操作 throughNetwork リソース プロバイダーに渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionSharedKey の Put 操作では、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity BeginUpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity BeginUpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As TagsObject) As VirtualNetworkGatewayConnectionListEntity" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            仮想ネットワーク ゲートウェイ接続のタグを更新する指定されたパラメーター。
            </param>
        <summary>
            仮想ネットワーク ゲートウェイ接続タグを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            仮想ネットワーク ゲートウェイ接続のタグを更新する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            仮想ネットワーク ゲートウェイ接続タグを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection CreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection CreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As VirtualNetworkGatewayConnection) As VirtualNetworkGatewayConnection" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            パラメーターが作成または更新仮想ネットワーク ゲートウェイの接続操作を指定します。
            </param>
        <summary>
            作成するか、指定されたリソース グループ内の仮想ネットワーク ゲートウェイ接続を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            パラメーターが作成または更新仮想ネットワーク ゲートウェイの接続操作を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたリソース グループ内の仮想ネットワーク ゲートウェイ接続を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Delete (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <summary>
            指定された仮想ネットワーク ゲートウェイの接続を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された仮想ネットワーク ゲートウェイの接続を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection Get (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection Get(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String) As VirtualNetworkGatewayConnection" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Get (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <summary>
            リソース グループによって指定された仮想ネットワーク ゲートウェイの接続を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; GetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; GetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループによって指定された仮想ネットワーク ゲートウェイの接続を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionSharedKey GetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey GetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String) As ConnectionSharedKey" />
      <MemberSignature Language="F#" Value="static member GetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続は、キー名を共有します。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionSharedKey の Get 操作では、ネットワーク リソース プロバイダーによって指定された仮想ネットワーク ゲートウェイ接続共有キーに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; GetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; GetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetSharedKeyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続は、キー名を共有します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionSharedKey の Get 操作では、ネットワーク リソース プロバイダーによって指定された仮想ネットワーク ゲートウェイ接続共有キーに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; List (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; List(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.List(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String) As IPage(Of VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <summary>
            リスト VirtualNetworkGatewayConnections 操作は、すべての仮想ネットワーク ゲートウェイ接続の作成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
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
            リスト VirtualNetworkGatewayConnections 操作は、すべての仮想ネットワーク ゲートウェイ接続の作成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; ListNext (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; ListNext(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualNetworkGatewayConnectionsOperations, nextPageLink As String) As IPage(Of VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            リスト VirtualNetworkGatewayConnections 操作は、すべての仮想ネットワーク ゲートウェイ接続の作成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
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
            リスト VirtualNetworkGatewayConnections 操作は、すべての仮想ネットワーク ゲートウェイ接続の作成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey ResetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey ResetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionResetSharedKey) As ConnectionResetSharedKey" />
      <MemberSignature Language="F#" Value="static member ResetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続は、共有キーの名前をリセットします。
            </param>
        <param name="parameters">
            開始する指定されたパラメーターは、ネットワーク リソース プロバイダーを仮想ネットワーク ゲートウェイ接続の共有のキー操作をリセットします。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionResetSharedKey 操作は、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーをリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; ResetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; ResetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ResetSharedKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続は、共有キーの名前をリセットします。
            </param>
        <param name="parameters">
            開始する指定されたパラメーターは、ネットワーク リソース プロバイダーを仮想ネットワーク ゲートウェイ接続の共有のキー操作をリセットします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionResetSharedKey 操作は、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーをリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionSharedKey SetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey SetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionSharedKey) As ConnectionSharedKey" />
      <MemberSignature Language="F#" Value="static member SetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続名です。
            </param>
        <param name="parameters">
            仮想ネットワークの設定を開始ゲートウェイ接続共有キー操作 throughNetwork リソース プロバイダーに渡されるパラメーター。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionSharedKey の Put 操作では、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; SetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; SetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;SetSharedKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続名です。
            </param>
        <param name="parameters">
            仮想ネットワークの設定を開始ゲートウェイ接続共有キー操作 throughNetwork リソース プロバイダーに渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            VirtualNetworkGatewayConnectionSharedKey の Put 操作では、指定されたリソース グループ リソース プロバイダーのネットワーク経由で渡された仮想ネットワーク ゲートウェイの接続の仮想ネットワーク ゲートウェイ接続共有キーを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity UpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity UpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As TagsObject) As VirtualNetworkGatewayConnectionListEntity" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTags (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            仮想ネットワーク ゲートウェイ接続のタグを更新する指定されたパラメーター。
            </param>
        <summary>
            仮想ネットワーク ゲートウェイ接続タグを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            仮想ネットワーク ゲートウェイの接続の名前。
            </param>
        <param name="parameters">
            仮想ネットワーク ゲートウェイ接続のタグを更新する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            仮想ネットワーク ゲートウェイ接続タグを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>