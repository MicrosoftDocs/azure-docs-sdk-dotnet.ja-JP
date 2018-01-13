<Type Name="ActivityLogsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityLogsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityLogsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityLogsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityLogsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ActivityLogsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; List (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery = null, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; List(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.EventData},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityLogsOperations, Optional odataQuery As ODataQuery(Of EventData) = null, Optional select As String = null) As IPage(Of EventData)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.List (operations, odataQuery, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            指定されたプロパティのみを持つイベントをフェッチするために使用します。&lt;br&gt;、 **$select**引数は、返されるプロパティ名のコンマ区切りリスト。 指定できる値は:*承認*、*クレーム*、 *correlationId*、*説明*、 *eventDataId*、 *eventName*、 *eventTimestamp*、 *httpRequest*、*レベル*、 *operationId*、 *operationName*、*プロパティ*、 *resourceGroupName*、 *resourceProviderName*、 *resourceId*、*ステータス*、 *submissionTimestamp*、*副状態*、 *subscriptionId*
            </param>
        <summary>
            動作状況のログのレコードの一覧を提供します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery = null, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; odataQuery, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.EventData},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListAsync (operations, odataQuery, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            指定されたプロパティのみを持つイベントをフェッチするために使用します。&lt;br&gt;、 **$select**引数は、返されるプロパティ名のコンマ区切りリスト。 指定できる値は:*承認*、*クレーム*、 *correlationId*、*説明*、 *eventDataId*、 *eventName*、 *eventTimestamp*、 *httpRequest*、*レベル*、 *operationId*、 *operationName*、*プロパティ*、 *resourceGroupName*、 *resourceProviderName*、 *resourceId*、*ステータス*、 *submissionTimestamp*、*副状態*、 *subscriptionId*
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            動作状況のログのレコードの一覧を提供します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt; ListNext (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt; ListNext(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNext(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityLogsOperations, nextPageLink As String) As IPage(Of EventData)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
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
            動作状況のログのレコードの一覧を提供します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Monitor.IActivityLogsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Monitor.IActivityLogsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Monitor.IActivityLogsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.ActivityLogsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Monitor.Models.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IActivityLogsOperations" RefType="this" />
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
            動作状況のログのレコードの一覧を提供します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>