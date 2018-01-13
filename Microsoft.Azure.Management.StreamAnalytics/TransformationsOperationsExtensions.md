<Type Name="TransformationsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TransformationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TransformationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TransformationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TransformationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            TransformationsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplace (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="transformation">
            新しい変換を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される変換の定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="ifMatch">
            変換の ETag です。 常に現在の変換を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しい変換を作成するが、既存の変換の更新を防ぐために使用できるようにします。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <summary>
            変換を作成するか、既存のストリーミング ジョブの下で、既存の変換を置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplaceAsync (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="transformation">
            新しい変換を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される変換の定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="ifMatch">
            変換の ETag です。 常に現在の変換を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しい変換を作成するが、既存の変換の更新を防ぐために使用できるようにします。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            変換を作成するか、既存のストリーミング ジョブの下で、既存の変換を置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Get (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Get(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITransformationsOperations, resourceGroupName As String, jobName As String, transformationName As String) As Transformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Get (operations, resourceGroupName, jobName, transformationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <summary>
            指定した変換の詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, transformationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した変換の詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Update (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Update(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Update (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="transformation">
            変換オブジェクトです。 既存の変換 (ie 対応するプロパティをここで指定したプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味既存の変換では、対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="ifMatch">
            変換の ETag です。 常に現在の変換を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <summary>
            既存のストリーミング ジョブの下にある既存の変換を更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブまたは変換の定義に影響を与えずに変換します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.UpdateAsync (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="transformation">
            変換オブジェクトです。 既存の変換 (ie 対応するプロパティをここで指定したプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味既存の変換では、対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="ifMatch">
            変換の ETag です。 常に現在の変換を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のストリーミング ジョブの下にある既存の変換を更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブまたは変換の定義に影響を与えずに変換します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>