<Type Name="FeaturesOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FeaturesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FeaturesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FeaturesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FeaturesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            FeaturesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Get (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Get(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFeaturesOperations, resourceProviderNamespace As String, featureName As String) As FeatureResult" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Get (operations, resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.FeatureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間の機能です。
            </param>
        <param name="featureName">
            取得する機能の名前です。
            </param>
        <summary>
            プレビュー機能は、指定した名前を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.GetAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間の機能です。
            </param>
        <param name="featureName">
            取得する機能の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プレビュー機能は、指定した名前を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; List (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; List(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IFeaturesOperations, resourceProviderNamespace As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.List (operations, resourceProviderNamespace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            機能を取得するためのリソース プロバイダーの名前空間。
            </param>
        <summary>
            サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAll (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAll(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAll(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IFeaturesOperations) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAllAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
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
            サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAllNext (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAllNext(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IFeaturesOperations, nextPageLink As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
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
            サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAllNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
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
            サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            機能を取得するためのリソース プロバイダーの名前空間。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IFeaturesOperations, nextPageLink As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
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
            サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
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
            サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Register (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Register(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Register(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Register (operations As IFeaturesOperations, resourceProviderNamespace As String, featureName As String) As FeatureResult" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Register (operations, resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.FeatureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="featureName">
            登録する機能の名前です。
            </param>
        <summary>
            サブスクリプションのプレビュー機能を登録します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;RegisterAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="featureName">
            登録する機能の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションのプレビュー機能を登録します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>