<Type Name="MobileServiceCollection&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class MobileServiceCollection&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;T,T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceCollection`1&lt;T&gt; extends Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2&lt;!T, !T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`1" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceCollection(Of T)&#xA;Inherits MobileServiceCollection(Of T, T)" />
  <TypeSignature Language="F#" Value="type MobileServiceCollection&lt;'T&gt; = class&#xA;    inherit MobileServiceCollection&lt;'T, 'T&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;T,T&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TTable">T</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TCollection">T</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">データ ソースとコレクション要素の型。</typeparam>
    <summary>
            ListView、GridView、ListBox などの Xaml コレクション制御によって簡単に使用されるようにモバイル サービスのクエリの結果をラップできる非同期データ ソース。
            </summary>
    <remarks>
            現在、データの読み込み、コントロールに通知する、およびページングを非同期的に処理されます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceCollection (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; query, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; query, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`1.#ctor(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IMobileServiceTableQuery(Of T), Optional pageSize As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'T&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt; * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'T&gt; (query, pageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="query">
            データを提供するデータ ソースのクエリです。
            </param>
        <param name="pageSize">
            要求ごとに要求された項目の数。
            </param>
        <summary>
            <see cref="T:IncrementalLoadingMobileServiceCollection{T}" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>