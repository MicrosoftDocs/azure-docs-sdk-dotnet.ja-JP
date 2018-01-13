<Type Name="ProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProvidersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ProvidersOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.GetAsync (operations, resourceProviderNamespace, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの Namespace です。
            </param>
        <param name="expand">
            $ は、クエリ パラメーターを展開します。 例: 使用 $ の展開応答に含めるプロパティのエイリアス、リソースの種類/エイリアスを = です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース プロバイダーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, Nullable&lt;int&gt; top = null, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListAsync (operations, top, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;ListAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="top">
            クエリ パラメーター。 Null が渡される場合は、すべての展開を返します。
            </param>
        <param name="expand">
            $ は、クエリ パラメーターを展開します。 例: 使用 $ の展開応答に含めるプロパティのエイリアス、リソースの種類/エイリアスを = です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース プロバイダーの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;ListNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
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
            リソース プロバイダーの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;RegisterAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの Namespace です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションで使用するプロバイダーを登録します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; UnregisterAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt; UnregisterAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.UnregisterAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnregisterAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions.UnregisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ProvidersOperationsExtensions/&lt;UnregisterAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの Namespace です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションからプロバイダーの登録を解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>