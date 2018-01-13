<Type Name="MobileServiceODataException" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceODataException">
  <TypeSignature Language="C#" Value="public class MobileServiceODataException : InvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceODataException extends System.InvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceODataException&#xA;Inherits InvalidOperationException" />
  <TypeSignature Language="F#" Value="type MobileServiceODataException = class&#xA;    inherit InvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.InvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            OData クエリの解析中に例外を表す例外の種類。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> クラスの新しいインスタンスを作成します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException (string message, int errorPos);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, int32 errorPos) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorPos As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException : string * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException (message, errorPos)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorPos" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="message">この例外のプレーンテキスト エラー メッセージ。</param>
        <param name="errorPos">エラーが存在する文字列内の位置。</param>
        <summary>エラー メッセージを使用して、<see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> クラスの新しいインスタンスを作成します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException (string message, int errorPos, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, int32 errorPos, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor(System.String,System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorPos As Integer, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException : string * int * Exception -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException (message, errorPos, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorPos" Type="System.Int32" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">この例外のプレーンテキスト エラー メッセージ。</param>
        <param name="errorPos">エラーが存在する文字列内の位置。</param>
        <param name="innerException">この例外がスローされる原因である内部例外。</param>
        <summary>エラー メッセージおよび内部例外を使用して、<see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" /> クラスの新しいインスタンスを作成します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorPosition">
      <MemberSignature Language="C#" Value="public int ErrorPosition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorPosition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.ErrorPosition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorPosition As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorPosition : int" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.ErrorPosition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーが存在する文字列内の位置
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>