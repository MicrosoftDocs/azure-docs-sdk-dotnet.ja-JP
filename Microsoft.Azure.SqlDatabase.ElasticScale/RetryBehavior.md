<Type Name="RetryBehavior" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior">
  <TypeSignature Language="C#" Value="public sealed class RetryBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryBehavior extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryBehavior" />
  <TypeSignature Language="F#" Value="type RetryBehavior = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            一時的なエラーを検出するために使用する再試行動作を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryBehavior (Func&lt;Exception,bool&gt; transientErrorDetector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class System.Exception, bool&gt; transientErrorDetector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.#ctor(System.Func{System.Exception,System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transientErrorDetector As Func(Of Exception, Boolean))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior : Func&lt;Exception, bool&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior transientErrorDetector" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transientErrorDetector" Type="System.Func&lt;System.Exception,System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="transientErrorDetector">特定の例外の一時的なエラーを検出する関数。
             関数は、一時的なものとして扱う必要がある例外の場合は true を返す必要があります。
            </param>
        <summary>
             インスタンスを初期化、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />クラス
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRetryBehavior">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior DefaultRetryBehavior { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior DefaultRetryBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultRetryBehavior As RetryBehavior" />
      <MemberSignature Language="F#" Value="member this.DefaultRetryBehavior : Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            既定の再試行動作を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定の再試行動作では、組み込みの一時的なものと見なされる例外のセットがあります。 作成して、カスタムを使用することがあります<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />一時的なものとして追加の例外を処理するためにオブジェクト。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>