<Type Name="VirtualNetworkGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewaysOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            VirtualNetworkGatewaysOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="parameters">
            作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された仮想ネットワーク ゲートウェイを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGeneratevpnclientpackageAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGenerateVpnProfileAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGenerateVpnProfileAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetAdvertisedRoutesAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="peer">
            ピアの IP アドレス
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; BeginGetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; BeginGetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetBgpPeerStatusAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="peer">
            状態を取得するピアの IP アドレス。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetLearnedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetLearnedRoutesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginResetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginResetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginResetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="gatewayVip">
            仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="parameters">
            作成または更新の各仮想ネットワーク ゲートウェイの操作に渡されるパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたリソース グループに仮想ネットワーク ゲートウェイを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された仮想ネットワーク ゲートウェイを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GeneratevpnclientpackageAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateVpnProfileAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GenerateVpnProfileAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAdvertisedRoutesAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="peer">
            ピアの IP アドレス
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            この操作は、仮想ネットワーク ゲートウェイが、指定したピアにアドバタイズするルートの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループによって指定された仮想ネットワーク ゲートウェイを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; GetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; GetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetBgpPeerStatusAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="peer">
            状態を取得するピアの IP アドレス。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            GetBgpPeerStatus 操作では、すべての BGP ピアの状態を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetLearnedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetLearnedRoutesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            この操作では、仮想ネットワーク ゲートウェイが学習したルートの一覧を取得は、BGP ピアから学習したルートを含むです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
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
            リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsNextAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
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
            リソース グループによってすべての仮想ネットワーク ゲートウェイを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; ResetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; ResetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ResetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ResetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="virtualNetworkGatewayName">
            仮想ネットワーク ゲートウェイの名前。
            </param>
        <param name="gatewayVip">
            仮想ネットワーク ゲートウェイの vip アドレスがアクティブ/アクティブ機能を有効にしているゲートウェイの開始のリセットを提供します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内の仮想ネットワーク ゲートウェイのプライマリをリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>