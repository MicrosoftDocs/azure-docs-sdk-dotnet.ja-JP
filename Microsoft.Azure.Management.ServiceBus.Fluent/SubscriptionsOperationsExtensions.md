<Type Name="SubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            SubscriptionsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner" />
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
        <param name="topicName">
            トピック名。
            </param>
        <param name="subscriptionName">
            サブスクリプションの名前。
            </param>
        <param name="parameters">
            サブスクリプション リソースを作成する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピック サブスクリプションを作成します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639385.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
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
        <param name="topicName">
            トピック名。
            </param>
        <param name="subscriptionName">
            サブスクリプションの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したトピックからサブスクリプションを削除します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639381.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
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
        <param name="topicName">
            トピック名。
            </param>
        <param name="subscriptionName">
            サブスクリプションの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したトピックのサブスクリプションの説明を返します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639402.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicAsync (operations, resourceGroupName, namespaceName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;ListByTopicAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
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
        <param name="topicName">
            トピック名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したトピックの下のすべてのサブスクリプションを一覧表示します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;ListByTopicNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
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
            指定したトピックの下のすべてのサブスクリプションを一覧表示します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>