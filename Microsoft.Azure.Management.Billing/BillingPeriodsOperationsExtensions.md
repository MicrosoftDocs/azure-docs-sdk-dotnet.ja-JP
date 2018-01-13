<Type Name="BillingPeriodsOperationsExtensions" FullName="Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BillingPeriodsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BillingPeriodsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BillingPeriodsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BillingPeriodsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            BillingPeriodsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Billing.Models.BillingPeriod Get (this Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string billingPeriodName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Billing.Models.BillingPeriod Get(class Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string billingPeriodName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.Get(Microsoft.Azure.Management.Billing.IBillingPeriodsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBillingPeriodsOperations, billingPeriodName As String) As BillingPeriod" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Billing.IBillingPeriodsOperations * string -&gt; Microsoft.Azure.Management.Billing.Models.BillingPeriod" Usage="Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.Get (operations, billingPeriodName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.BillingPeriod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IBillingPeriodsOperations" RefType="this" />
        <Parameter Name="billingPeriodName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="billingPeriodName">
            BillingPeriod リソースの名前。
            </param>
        <summary>
            名前付きの請求期間を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt; GetAsync (this Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string billingPeriodName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt; GetAsync(class Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string billingPeriodName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Billing.IBillingPeriodsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Billing.IBillingPeriodsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;" Usage="Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.GetAsync (operations, billingPeriodName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IBillingPeriodsOperations" RefType="this" />
        <Parameter Name="billingPeriodName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="billingPeriodName">
            BillingPeriod リソースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前付きの請求期間を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt; List (this Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt; List(class Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.List(Microsoft.Azure.Management.Billing.IBillingPeriodsOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBillingPeriodsOperations, Optional filter As String = null, Optional skiptoken As String = null, Optional top As Nullable(Of Integer) = null) As IPage(Of BillingPeriod)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Billing.IBillingPeriodsOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;" Usage="Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.List (operations, filter, skiptoken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IBillingPeriodsOperations" RefType="this" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="filter">
            BillingPeriodEndDate によって課金期間をフィルター処理に使用可能性があります。 フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。 これはサポートされていません"ne"'または' または 'not' です。
            </param>
        <param name="skiptoken">
            Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。
            前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。
            </param>
        <param name="top">
            最新の N の請求期間に結果の数を制限するために使用可能性があります。
            </param>
        <summary>
            発生の逆順でサブスクリプションの利用可能な請求期間を一覧表示します。
            <see href="https://go.microsoft.com/fwlink/?linkid=844490" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt; ListAsync (this Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt; ListAsync(class Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Billing.IBillingPeriodsOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Billing.IBillingPeriodsOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.ListAsync (operations, filter, skiptoken, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IBillingPeriodsOperations" RefType="this" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="filter">
            BillingPeriodEndDate によって課金期間をフィルター処理に使用可能性があります。 フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。 これはサポートされていません"ne"'または' または 'not' です。
            </param>
        <param name="skiptoken">
            Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。
            前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。
            </param>
        <param name="top">
            最新の N の請求期間に結果の数を制限するために使用可能性があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            発生の逆順でサブスクリプションの利用可能な請求期間を一覧表示します。
            <see href="https://go.microsoft.com/fwlink/?linkid=844490" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt; ListNext (this Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt; ListNext(class Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.ListNext(Microsoft.Azure.Management.Billing.IBillingPeriodsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBillingPeriodsOperations, nextPageLink As String) As IPage(Of BillingPeriod)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Billing.IBillingPeriodsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;" Usage="Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IBillingPeriodsOperations" RefType="this" />
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
            発生の逆順でサブスクリプションの利用可能な請求期間を一覧表示します。
            <see href="https://go.microsoft.com/fwlink/?linkid=844490" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Billing.IBillingPeriodsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Billing.IBillingPeriodsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Billing.IBillingPeriodsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.BillingPeriodsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.BillingPeriod&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IBillingPeriodsOperations" RefType="this" />
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
            発生の逆順でサブスクリプションの利用可能な請求期間を一覧表示します。
            <see href="https://go.microsoft.com/fwlink/?linkid=844490" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>