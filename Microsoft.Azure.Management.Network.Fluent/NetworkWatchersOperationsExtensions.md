<Type Name="NetworkWatchersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkWatchersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkWatchersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkWatchersOperationsExtensions = class" />
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
            NetworkWatchersOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; BeginCheckConnectivityAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; BeginCheckConnectivityAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCheckConnectivityAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginCheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginCheckConnectivityAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="networkWatcherName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したネットワーク監視リソースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginGetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginGetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetFlowLogStatusAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetFlowLogStatusAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ネットワーク ウォッチャー リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="targetResourceId">
            ターゲット リソースでは、フローのログ記録の状態を取得する場所です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            フローのクエリの状態は、指定されたリソースにログオンします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; BeginGetNextHopAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; BeginGetNextHopAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetNextHopAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetNextHopAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="parameters">
            送信元と送信先のエンドポイントを定義するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した VM から次のホップを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="parameters">
            トラブルシューティングのリソースを定義するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したリソースに対するトラブルシューティングを開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; BeginGetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetTroubleshootingResultAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="targetResourceId">
            クエリのトラブルシューティングの結果をターゲット リソース ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; BeginGetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; BeginGetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginGetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginGetVMSecurityRulesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="targetResourceId">
            ターゲットの VM の ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した VM で構成され、有効なセキュリティ グループの規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginSetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; BeginSetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginSetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginSetFlowLogConfigurationAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ネットワーク ウォッチャー リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="parameters">
            フローのログの構成を定義するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソースのフローのログを構成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginVerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; BeginVerifyIPFlowAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; BeginVerifyIPFlowAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginVerifyIPFlowAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.BeginVerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;BeginVerifyIPFlowAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="parameters">
            検証する IP フローを定義するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckConnectivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; CheckConnectivityAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt; CheckConnectivityAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CheckConnectivityAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckConnectivityAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CheckConnectivityAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;CheckConnectivityAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ConnectivityParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="networkWatcherName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="parameters">
            ネットワーク ウォッチャー リソースを定義するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたリソース グループにネットワーク ウォッチャーを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したネットワーク監視リソースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループによって指定されたネットワーク ウォッチャーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFlowLogStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; GetFlowLogStatusAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; GetFlowLogStatusAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFlowLogStatusAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetFlowLogStatusAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetFlowLogStatusAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ネットワーク ウォッチャー リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="targetResourceId">
            ターゲット リソースでは、フローのログ記録の状態を取得する場所です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            フローのクエリの状態は、指定されたリソースにログオンします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextHopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; GetNextHopAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt; GetNextHopAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetNextHopAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNextHopAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetNextHopAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetNextHopAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="parameters">
            送信元と送信先のエンドポイントを定義するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した VM から次のホップを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopologyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt; GetTopologyAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt; GetTopologyAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTopologyAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTopologyAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTopologyAsync (operations, resourceGroupName, networkWatcherName, targetResourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTopologyAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="targetResourceGroupName">
            トポロジを実行するターゲット リソース グループの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループによって、現在のネットワーク トポロジを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="parameters">
            トラブルシューティングのリソースを定義するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したリソースに対するトラブルシューティングを開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTroubleshootingResultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingResultAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt; GetTroubleshootingResultAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTroubleshootingResultAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetTroubleshootingResultAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetTroubleshootingResultAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="targetResourceId">
            クエリのトラブルシューティングの結果をターゲット リソース ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したリソースに対して最後に完了したトラブルシューティングの結果を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVMSecurityRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; GetVMSecurityRulesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt; GetVMSecurityRulesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, string targetResourceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVMSecurityRulesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.GetVMSecurityRulesAsync (operations, resourceGroupName, networkWatcherName, targetResourceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;GetVMSecurityRulesAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="targetResourceId">
            ターゲットの VM の ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した VM で構成され、有効なセキュリティ グループの規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;ListAllAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
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
            サブスクリプションによってすべてのネットワーク監視を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkWatcherInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
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
            リソース グループによってすべてのネットワーク監視を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetFlowLogConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; SetFlowLogConfigurationAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt; SetFlowLogConfigurationAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetFlowLogConfigurationAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.SetFlowLogConfigurationAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;SetFlowLogConfigurationAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ネットワーク ウォッチャー リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="parameters">
            フローのログの構成を定義するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソースのフローのログを構成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyIPFlowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; VerifyIPFlowAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt; VerifyIPFlowAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations operations, string resourceGroupName, string networkWatcherName, class Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync(Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyIPFlowAsync : Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions.VerifyIPFlowAsync (operations, resourceGroupName, networkWatcherName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkWatchersOperationsExtensions/&lt;VerifyIPFlowAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkWatchersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="parameters">
            検証する IP フローを定義するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在構成されている NSG ルールを指定した位置に指定した VM から IP フローを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>