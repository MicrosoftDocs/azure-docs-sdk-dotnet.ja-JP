<Type Name="DeletedWebAppsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeletedWebAppsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeletedWebAppsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeletedWebAppsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeletedWebAppsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            DeletedWebAppsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations" RefType="this" />
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
            削除したすべてのアプリのサブスクリプションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            削除したすべてのアプリのサブスクリプションを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            取得では、サブスクリプションで web アプリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            取得では、サブスクリプションで web アプリを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations" RefType="this" />
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
            取得では、サブスクリプションで web アプリを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            取得では、サブスクリプションで web アプリを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DeletedWebAppsOperationsExtensions/&lt;ListNextAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDeletedWebAppsOperations" RefType="this" />
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
            削除したすべてのアプリのサブスクリプションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            削除したすべてのアプリのサブスクリプションを取得します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>