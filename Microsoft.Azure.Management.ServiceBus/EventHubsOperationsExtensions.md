<Type Name="EventHubsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EventHubsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventHubsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventHubsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EventHubsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            EventHubsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByNamespace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt; ListByNamespace (this Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt; ListByNamespace(class Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespace(Microsoft.Azure.Management.ServiceBus.IEventHubsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespace (operations As IEventHubsOperations, resourceGroupName As String, namespaceName As String) As IPage(Of Eventhub)" />
      <MemberSignature Language="F#" Value="static member ListByNamespace : Microsoft.Azure.Management.ServiceBus.IEventHubsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;" Usage="Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespace (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <summary>
            サービス バス Namespace 内のすべてのイベント ハブを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt; ListByNamespaceAsync (this Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt; ListByNamespaceAsync(class Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespaceAsync(Microsoft.Azure.Management.ServiceBus.IEventHubsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceAsync : Microsoft.Azure.Management.ServiceBus.IEventHubsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespaceAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions/&lt;ListByNamespaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IEventHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サービス バス Namespace 内のすべてのイベント ハブを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt; ListByNamespaceNext (this Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt; ListByNamespaceNext(class Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespaceNext(Microsoft.Azure.Management.ServiceBus.IEventHubsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespaceNext (operations As IEventHubsOperations, nextPageLink As String) As IPage(Of Eventhub)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNext : Microsoft.Azure.Management.ServiceBus.IEventHubsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;" Usage="Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IEventHubsOperations" RefType="this" />
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
            サービス バス Namespace 内のすべてのイベント ハブを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt; ListByNamespaceNextAsync (this Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt; ListByNamespaceNextAsync(class Microsoft.Azure.Management.ServiceBus.IEventHubsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespaceNextAsync(Microsoft.Azure.Management.ServiceBus.IEventHubsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNextAsync : Microsoft.Azure.Management.ServiceBus.IEventHubsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions.ListByNamespaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.EventHubsOperationsExtensions/&lt;ListByNamespaceNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Eventhub&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IEventHubsOperations" RefType="this" />
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
            サービス バス Namespace 内のすべてのイベント ハブを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>