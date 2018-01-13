<Type Name="NetworkInterfaceIPConfigurationsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkInterfaceIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkInterfaceIPConfigurationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkInterfaceIPConfigurationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceIPConfigurationsOperationsExtensions = class" />
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
            NetworkInterfaceIPConfigurationsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration Get (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration Get(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkInterfaceIPConfigurationsOperations, resourceGroupName As String, networkInterfaceName As String, ipConfigurationName As String) As NetworkInterfaceIPConfiguration" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.Get (operations, resourceGroupName, networkInterfaceName, ipConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkInterfaceName">
            ネットワーク インターフェイスの名前。
            </param>
        <param name="ipConfigurationName">
            Ip 構成の名前の名前。
            </param>
        <summary>
            指定したネットワーク インターフェイス ip 構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, string ipConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.GetAsync (operations, resourceGroupName, networkInterfaceName, ipConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkInterfaceName">
            ネットワーク インターフェイスの名前。
            </param>
        <param name="ipConfigurationName">
            Ip 構成の名前の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したネットワーク インターフェイス ip 構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; List (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; List(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkInterfaceIPConfigurationsOperations, resourceGroupName As String, networkInterfaceName As String) As IPage(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.List (operations, resourceGroupName, networkInterfaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkInterfaceName">
            ネットワーク インターフェイスの名前。
            </param>
        <summary>
            ネットワーク インターフェイスのすべての ip 構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkInterfaceName">
            ネットワーク インターフェイスの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ネットワーク インターフェイスのすべての ip 構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListNext (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ListNext(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INetworkInterfaceIPConfigurationsOperations, nextPageLink As String) As IPage(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
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
            ネットワーク インターフェイスのすべての ip 構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkInterfaceIPConfigurationsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkInterfaceIPConfigurationsOperations" RefType="this" />
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
            ネットワーク インターフェイスのすべての ip 構成を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>