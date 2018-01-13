<Type Name="IServiceRemotingRequestMessageBody" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="F#" Value="type IServiceRemotingRequestMessageBody = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リモート処理要求の要求メッセージの本文を提供するために実装する必要があります、インターフェイスを定義します。
            これは、パラメーターのリモート処理メソッドがすべて含まれます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetParameter">
      <MemberSignature Language="C#" Value="public object GetParameter (int position, string parameName, Type paramType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetParameter(int32 position, string parameName, class System.Type paramType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody.GetParameter(System.Int32,System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetParameter (position As Integer, parameName As String, paramType As Type) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetParameter : int * string * Type -&gt; obj" Usage="iServiceRemotingRequestMessageBody.GetParameter (position, parameName, paramType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int32" />
        <Parameter Name="parameName" Type="System.String" />
        <Parameter Name="paramType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="position">リモート処理メソッドのパラメーターの位置。</param>
        <param name="parameName">リモート処理メソッドのパラメーター名</param>
        <param name="paramType">パラメーターのタイプ</param>
        <summary>
            サービスのリモート処理メソッドにディスパッチする前に要求の本体からパラメーターの取得に使用されます。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetParameter">
      <MemberSignature Language="C#" Value="public void SetParameter (int position, string parameName, object parameter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetParameter(int32 position, string parameName, object parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody.SetParameter(System.Int32,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetParameter (position As Integer, parameName As String, parameter As Object)" />
      <MemberSignature Language="F#" Value="abstract member SetParameter : int * string * obj -&gt; unit" Usage="iServiceRemotingRequestMessageBody.SetParameter (position, parameName, parameter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int32" />
        <Parameter Name="parameName" Type="System.String" />
        <Parameter Name="parameter" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="position">リモート処理メソッドのパラメーターの位置。</param>
        <param name="parameName">リモート処理メソッドのパラメーター名</param>
        <param name="parameter">パラメーター値</param>
        <summary>
            この Api は、リモート処理メソッドのパラメーターを設定、要求のシリアル化/ディスパッチの前に呼び出されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>