<Type Name="GroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type GroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            GroupsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMemberAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddMemberAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddMemberAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.AddMemberAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddMemberAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.AddMemberAsync (operations, groupObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;AddMemberAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="groupObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="groupObjectId">
            メンバーを追加するグループのオブジェクト ID。
            </param>
        <param name="parameters">
            Https://graph.windows.net/0b1f9851-1bf0-433f-aec3-cb9272f093dc/directoryObjects/f260bbc4-c254-447b-94cf-293b5ec434dd など、メンバー オブジェクトの URL です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            グループにメンバーを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; CreateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; CreateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.CreateAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;CreateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            作成するグループのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ディレクトリ内のグループを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.DeleteAsync (operations, groupObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="groupObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="groupObjectId">
            削除するグループのオブジェクト ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ディレクトリからグループを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; GetAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; GetAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            グループの情報を取得する対象のユーザーのオブジェクト ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            取得は、ディレクトリから情報をグループ化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGroupMembersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGroupMembersAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetGroupMembersAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            取得するメンバーのグループのオブジェクト ID。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            グループのメンバーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGroupMembersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGroupMembersNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetGroupMembersNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextLink">
            一覧表示操作の次のリンク。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            グループのメンバーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMemberGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetMemberGroupsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetMemberGroupsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetMemberGroupsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMemberGroupsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetMemberGroupsAsync (operations, objectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetMemberGroupsAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="objectId">
            グループ メンバーシップを取得する対象のグループのオブジェクト ID。
            </param>
        <param name="parameters">
            フィルターのパラメーターをグループ化します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたグループがメンバーであるグループのオブジェクト Id のコレクションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsMemberOfAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt; IsMemberOfAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt; IsMemberOfAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.IsMemberOfAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IsMemberOfAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.IsMemberOfAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;IsMemberOfAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            チェックのグループ メンバーシップのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたユーザー、グループ、連絡先、またはサービス プリンシパル、指定されたグループの直接または推移的メンバーであるかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在のテナントのグループの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextLink">
            一覧表示操作の次のリンク。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在のテナントのグループの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveMemberAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveMemberAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, string memberObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveMemberAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, string memberObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.RemoveMemberAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveMemberAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.RemoveMemberAsync (operations, groupObjectId, memberObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;RemoveMemberAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="groupObjectId" Type="System.String" />
        <Parameter Name="memberObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="groupObjectId">
            グループからメンバーを削除する対象のオブジェクト ID。
            </param>
        <param name="memberObjectId">
            メンバー オブジェクトの id
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            グループからメンバーを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>