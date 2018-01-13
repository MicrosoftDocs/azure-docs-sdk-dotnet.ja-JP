<Type Name="TopicsOperationsExtensions" FullName="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopicsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopicsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopicsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopicsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            TopicsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic BeginCreateOrUpdate (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic BeginCreateOrUpdate(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ITopicsOperations, resourceGroupName As String, topicName As String, topicInfo As Topic) As Topic" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, topicName, topicInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="topicInfo">
            トピックの情報
            </param>
        <summary>
            トピックを作成する
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターを使用して、新しいトピックを非同期に作成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, topicName, topicInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="topicInfo">
            トピックの情報
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックを作成する
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターを使用して、新しいトピックを非同期に作成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ITopicsOperations, resourceGroupName As String, topicName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDelete (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <summary>
            トピックを削除する
            </summary>
        <remarks>
            既存のトピックを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックを削除する
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存のトピックを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic BeginUpdate (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic BeginUpdate(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As ITopicsOperations, resourceGroupName As String, topicName As String, Optional tags As IDictionary(Of String, String) = null) As Topic" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdate (operations, resourceGroupName, topicName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="tags">
            リソースのタグ
            </param>
        <summary>
            トピックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターでトピックを非同期に更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginUpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginUpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, topicName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="tags">
            リソースのタグ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターでトピックを非同期に更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic CreateOrUpdate (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic CreateOrUpdate(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITopicsOperations, resourceGroupName As String, topicName As String, topicInfo As Topic) As Topic" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, topicName, topicInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="topicInfo">
            トピックの情報
            </param>
        <summary>
            トピックを作成する
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターを使用して、新しいトピックを非同期に作成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, topicName, topicInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="topicInfo">
            トピックの情報
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックを作成する
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターを使用して、新しいトピックを非同期に作成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Delete(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITopicsOperations, resourceGroupName As String, topicName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Delete (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <summary>
            トピックを削除する
            </summary>
        <remarks>
            既存のトピックを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.DeleteAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックを削除する
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存のトピックを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic Get (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic Get(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Get(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITopicsOperations, resourceGroupName As String, topicName As String) As Topic" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Get (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <summary>
            トピックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックのプロパティを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; GetAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; GetAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.GetAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックのプロパティを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListByResourceGroup (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListByResourceGroup(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As ITopicsOperations, resourceGroupName As String) As IEnumerable(Of Topic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <summary>
            リソース グループ下にあるトピックをリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループの下のすべてのトピックを一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ下にあるトピックをリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループの下のすべてのトピックを一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListBySubscription (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListBySubscription(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscription(Microsoft.Azure.Management.EventGrid.ITopicsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscription (operations As ITopicsOperations) As IEnumerable(Of Topic)" />
      <MemberSignature Language="F#" Value="static member ListBySubscription : Microsoft.Azure.Management.EventGrid.ITopicsOperations -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            Azure サブスクリプションの下にあるトピックをリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Azure サブスクリプションの下のすべてのトピックを一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListBySubscriptionAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
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
            Azure サブスクリプションの下にあるトピックをリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Azure サブスクリプションの下のすべてのトピックを一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt; ListEventTypes (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt; ListEventTypes(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypes(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventTypes (operations As ITopicsOperations, resourceGroupName As String, providerNamespace As String, resourceTypeName As String, resourceName As String) As IEnumerable(Of EventType)" />
      <MemberSignature Language="F#" Value="static member ListEventTypes : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypes (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="providerNamespace">
            トピックのプロバイダーの Namespace
            </param>
        <param name="resourceTypeName">
            トピックの種類の名前
            </param>
        <param name="resourceName">
            トピックの名前
            </param>
        <summary>
            トピック イベントの種類の一覧
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックの一覧のイベントの種類
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt; ListEventTypesAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt; ListEventTypesAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypesAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventTypesAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypesAsync (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListEventTypesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="providerNamespace">
            トピックのプロバイダーの Namespace
            </param>
        <param name="resourceTypeName">
            トピックの種類の名前
            </param>
        <param name="resourceName">
            トピックの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピック イベントの種類の一覧
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックの一覧のイベントの種類
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharedAccessKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys ListSharedAccessKeys (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys ListSharedAccessKeys(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeys(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSharedAccessKeys (operations As ITopicsOperations, resourceGroupName As String, topicName As String) As TopicSharedAccessKeys" />
      <MemberSignature Language="F#" Value="static member ListSharedAccessKeys : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeys (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <summary>
            トピックのキーの一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックへの公開に使用される 2 つのキーを一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharedAccessKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; ListSharedAccessKeysAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; ListSharedAccessKeysAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeysAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSharedAccessKeysAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeysAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListSharedAccessKeysAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックのキーの一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックへの公開に使用される 2 つのキーを一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys RegenerateKey (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys RegenerateKey(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As ITopicsOperations, resourceGroupName As String, topicName As String, keyName As String) As TopicSharedAccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKey (operations, resourceGroupName, topicName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="keyName">
            Key1、key2 または再生成するキーの名前
            </param>
        <summary>
            トピックのキーを再生成
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックの共有アクセス キーを再生成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, topicName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="keyName">
            Key1、key2 または再生成するキーの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックのキーを再生成
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックの共有アクセス キーを再生成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic Update (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic Update(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Update(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ITopicsOperations, resourceGroupName As String, topicName As String, Optional tags As IDictionary(Of String, String) = null) As Topic" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Update (operations, resourceGroupName, topicName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="tags">
            リソースのタグ
            </param>
        <summary>
            トピックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターでトピックを非同期に更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; UpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; UpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.UpdateAsync (operations, resourceGroupName, topicName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicName">
            トピックの名前
            </param>
        <param name="tags">
            リソースのタグ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたパラメーターでトピックを非同期に更新します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>